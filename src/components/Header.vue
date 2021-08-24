<template>
  <nav class="navbar">
    <i class="fa fa-home" aria-hidden="true" @click="$emit('navigate', 'home')"></i>
    <i class="fa fa-user" aria-hidden="true" @click="$emit('navigate', 'profile')"></i>
    <i class="fa fa-code" aria-hidden="true" @click="$emit('navigate', 'code')"></i>
    <i class="fa fa-pencil-square-o" aria-hidden="true" @click="$emit('navigate', 'edit')"></i>
  </nav>
</template>
<script>
export default{
  name: 'Header',
  
}

</script>