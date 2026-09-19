<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ogxgiopnw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:tawakkalna" /></template>
<style>
.ogxgiopnw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M18.942 39.992a7.4 7.4 0 0 1-5.251-2.176l-7.016-7.015a7.426 7.426 0 0 1 10.503-10.502l1.764 1.764l11.88-11.88a7.427 7.427 0 0 1 10.503 10.503L24.193 37.817a7.4 7.4 0 0 1-5.251 2.175");
}

</style>
