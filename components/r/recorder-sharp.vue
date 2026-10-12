<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="i5aqwgzqx"/><path class="p9jcxcb3f"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:recorder-sharp" /></template>
<style>
.i5aqwgzqx {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.5 2.75h5V9h-5zM11 6h2m-2 3h2.75v7.75q0 .75.19 1.47l.62 2.31l.19.72h-5.5l.19-.72l.62-2.31q.19-.72.19-1.47V9z");
}

.p9jcxcb3f {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 12h.01M12 15h.01");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>
