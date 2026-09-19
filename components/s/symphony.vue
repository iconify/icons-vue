<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="vba_d8b3d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:symphony" /></template>
<style>
.vba_d8b3d {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M42.5 21.697v4.74m-7.4-13.374v21.678M27.7 5.664v32.092m-7.4-27.512v32.092M12.9 14.41v19.044M5.5 19.65v8.928");
}

</style>
