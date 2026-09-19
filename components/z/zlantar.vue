<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="rhmx8ibyk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:zlantar" /></template>
<style>
.rhmx8ibyk {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M10.212 10.212c7.615-7.616 19.962-7.616 27.577 0L10.21 37.789c7.616 7.615 19.963 7.615 27.578 0");
}

</style>
