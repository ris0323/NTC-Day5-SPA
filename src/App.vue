<template>
  <NavbarComponent />
  <router-view/>
</template>
<script>
import NavbarComponent from '@/components/NavbarCompontent.vue'
export default {
    component: {
        NavbarComponent
    }
}
</script>
<style>
  body{
      margin:0px
  }
  </style>
