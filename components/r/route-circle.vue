<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="p_lkap-rx"/><path class="yfd5yjbht"/><path class="jtzrmm_7j"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:route-circle" /></template>
<style>
.jtzrmm_7j {
  d: path("M18.5 13.5c-2-2-3.25-3.75-3.25-6a3.25 3.25 0 0 1 6.5 0c0 2.25-1.25 4-3.25 6Z");
}

.p_lkap-rx {
  d: path("M10.5 5.5a8 8 0 1 0 8 8");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.yfd5yjbht {
  fill: currentColor;
  d: path("M8.75 5.5a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0Z");
}

</style>
