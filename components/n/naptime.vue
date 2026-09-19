<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="kvw0yxrau"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:naptime" /></template>
<style>
.kvw0yxrau {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24.474 9.641H43.5L24.474 38.359H43.5m-39-19.627h14.774L4.5 38.307h14.774");
}

</style>
