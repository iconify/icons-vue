<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="bazq81bsf"/><path class="lox42ospd"/><path class="d3xn50bni"/><path class="oy7fa3gbk"/><path class="dafu-cchc"/><path class="wskxlyzso"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:visa-duotone-bold" /></template>
<style>
.bazq81bsf {
  fill: currentColor;
  d: path("M4 4a2 2 0 0 1 2 -2h12a2 2 0 0 1 2 2v16a2 2 0 0 1 -2 2H6a2 2 0 0 1 -2 -2Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.d3xn50bni {
  d: path("M4 4a2 2 0 0 1 2 -2h12a2 2 0 0 1 2 2v16a2 2 0 0 1 -2 2H6a2 2 0 0 1 -2 -2Z");
}

.dafu-cchc {
  d: path("M10 8h7v8h-7Z");
}

.lox42ospd {
  fill: currentColor;
  d: path("M10 8h7v8h-7Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.oy7fa3gbk {
  d: path("M8 2v20");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.wskxlyzso {
  d: path("M12 12h3");
}

</style>
