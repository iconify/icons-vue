<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><circle class="jus0noe8b"/><path class="liqkfyb5a"/><path class="qaeb5k2ag"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:space-helmet-visor" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jus0noe8b {
  cx: 12px;
  cy: 10.75px;
  r: 8px;
}

.liqkfyb5a {
  d: path("M6.5 9.75C6.5 8 8.95 6.5 12 6.5s5.5 1.5 5.5 3.25v1c0 3.1-2.45 5.25-5.5 5.25s-5.5-2.15-5.5-5.25Z");
}

.qaeb5k2ag {
  d: path("M9 10.25c.6-1 1.6-1.5 2.75-1.5M7.5 21.25h9");
}

</style>
