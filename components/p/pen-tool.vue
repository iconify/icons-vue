<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="r6_14_bxb"/><circle class="jb8wwbf-o"/><rect class="d0av090xt"/><path class="ob1zbkb3d"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:pen-tool" /></template>
<style>
.d0av090xt {
  width: 4px;
  height: 4px;
  x: 10px;
  y: 17.25px;
  rx: 1px;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jb8wwbf-o {
  cx: 12px;
  cy: 10px;
  r: 1.25px;
}

.ob1zbkb3d {
  d: path("M3.75 19.25H7.5m9 0h3.75");
}

.r6_14_bxb {
  d: path("M12 2.75L17.15 8a1.5 1.5 0 0 1 .2 1.7L15 14.25H9L6.65 9.7a1.5 1.5 0 0 1 .2-1.7Zm0 2v4");
}

</style>
