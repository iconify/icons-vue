<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="chwfr3btt"/><path class="uw59zbbfm"/><path class="t-tlxbnvp"/><path class="sk9ov1b7d"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:mcp-resource-list-duotone-bold" /></template>
<style>
.chwfr3btt {
  fill: currentColor;
  d: path("M13 2h-3L7 5v12h10V7");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.sk9ov1b7d {
  d: path("M16 7h-3l-3 3v12h10V12");
}

.t-tlxbnvp {
  d: path("M13 2h-3L7 5v12h10V7");
}

.uw59zbbfm {
  fill: currentColor;
  d: path("M16 7h-3l-3 3v12h10V12");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
