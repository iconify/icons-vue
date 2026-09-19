<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="vs_11l_1t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:wallet-of-satoshi" /></template>
<style>
.vs_11l_1t {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M17.037 4.5h15.646a.884.884 0 0 1 .785 1.29L27.71 16.937a.83.83 0 0 0 .737 1.21h6.572c.968 0 1.494 1.133.87 1.872L16.054 43.5l3.316-16.831a.728.728 0 0 0-.714-.869h-6.175a.64.64 0 0 1-.628-.77L15.86 5.463c.114-.56.607-.962 1.178-.962");
}

</style>
