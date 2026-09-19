<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="pxzi0db5l"/><path class="s9q_ufbpw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:temu" /></template>
<style>
.pxzi0db5l {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M35.761 40.397a7.74 7.74 0 0 0 7.726-8.187l-.715-12.325c-.4-6.895-6.107-12.282-13.014-12.282H18.242c-6.907 0-12.614 5.387-13.014 12.282L4.513 32.21a7.74 7.74 0 0 0 7.726 8.187z");
}

.s9q_ufbpw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M16.812 16.91a7.188 7.188 0 1 0 14.377 0");
}

</style>
