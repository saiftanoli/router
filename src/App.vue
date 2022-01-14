<template>
<router-link to ="/"> Home </router-link> <br />
<router-link to ="/login"> Login </router-link> <br />
<router-link to ="/profile"> Profile </router-link> <br />

<router-view></router-view>
</template>

<script>
export default { 
  name: 'App',
}
</script>
