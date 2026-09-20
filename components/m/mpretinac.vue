<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="s-l8efb_x"/><path class="ckp2kogjs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:mpretinac" /></template>
<style>
.ckp2kogjs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M15.912 9.968h16.176c.61 0 1.105.495 1.105 1.105V27.25c0 .61-.495 1.105-1.105 1.105h-2.245a1.374 1.374 0 0 0-1.24 1.965l1.413 2.971l-7.407-4.76a1.1 1.1 0 0 0-.598-.176h-6.099c-.61 0-1.105-.495-1.105-1.105V11.073c0-.61.495-1.105 1.105-1.105");
}

.s-l8efb_x {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M37.525 4.5h-27.05c-1.02 0-1.848.828-1.848 1.849v27.049c0 1.02.827 1.848 1.848 1.848h3.754a2.298 2.298 0 0 1 2.075 3.286L13.94 43.5l12.387-7.96a1.85 1.85 0 0 1 1-.293h10.199c1.02 0 1.848-.828 1.848-1.849V6.348c0-1.02-.827-1.848-1.848-1.848");
}

</style>
