<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="wyejuibgb"/><path class="xzaqveb7e"/><path class="szb175cxl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:so-net" /></template>
<style>
.szb175cxl {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M31.035 32.206c.285 2.588-1.068 3.284-1.41 3.476c-1.235.691-2.148-.274-3.104-2.522c-.689-1.617-1.555-5.43-1.116-6.766c.205-.622 1.684.697 2.04 1.313");
}

.wyejuibgb {
  cx: 32.904px;
  cy: 27.033px;
  r: 5.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.xzaqveb7e {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M31.035 32.206c1.157 3.974-1.447 9.104-4.862 11.294L9.596 37.278c4.618-2.926 7.99-11.092 4.226-15.409l-1.25-1.433C8.662 15.953 12.564 7.23 16.628 4.5l15.494 9.552c-3.149 2.14-6.17 8.328-4.678 12.604");
}

</style>
