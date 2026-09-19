<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="s14494bvk"/><circle class="wdk07ew5o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:openanime" /></template>
<style>
.s14494bvk {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M33.071 17.852a3.425 3.425 0 0 1-6.85 0V6.925a3.425 3.425 0 0 1 6.85 0zm-15.219-2.923a3.425 3.425 0 0 1 0 6.85H6.925a3.425 3.425 0 0 1 0-6.85zm-2.923 15.219a3.425 3.425 0 0 1 6.85 0v10.927a3.425 3.425 0 0 1-6.85 0zm15.219 2.923a3.425 3.425 0 0 1 0-6.85h10.927a3.425 3.425 0 0 1 0 6.85z");
}

.wdk07ew5o {
  cx: 24px;
  cy: 24px;
  r: 2.437px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
