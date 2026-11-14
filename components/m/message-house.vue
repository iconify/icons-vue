<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ff33hgbmt"/><path class="hzoqz_bfi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:message-house" /></template>
<style>
.ff33hgbmt {
  d: path("M11.844 20.5H3.5v-10L12 3.25l8.5 7.25v.756");
}

.hzoqz_bfi {
  d: path("M7.5 20.5v-5q0-.098.019-.195t.057-.188t.093-.173t.124-.151t.151-.124t.173-.093t.188-.057t.195-.019h2q.192 0 .371.071q.179.072.318.204m.311 4.997v.728M15 14h5a1 1 0 0 1 1 1v3a1 1 0 0 1-1 1h-3l-2 2v-2a1 1 0 0 1-1-1v-3a1 1 0 0 1 1-1Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
