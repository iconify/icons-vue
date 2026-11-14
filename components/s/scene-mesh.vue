<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="d_v4kv01r"/><path class="xq0ikof0c"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:scene-mesh" /></template>
<style>
.d_v4kv01r {
  d: path("M2.5 8H16v13.5H2.5Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.xq0ikof0c {
  d: path("M2.5 8L8 2.5h13.5V16L16 21.5M16 8l5.5-5.5M2.5 8L16 21.5");
}

</style>
