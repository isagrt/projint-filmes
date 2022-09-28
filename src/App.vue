<script setup>
import { RouterView } from "vue-router";
import HeaderComp from "@/components/template/HeaderComp.vue";
import CardsComp from "@/components/template/CardsComp.vue";
import FooterComp from "@/components/template/FooterComp.vue";
</script>

<template>
  <HeaderComp />
  <CardsComp />
  <RouterView />
  <FooterComp />
</template>

<style>

</style>
