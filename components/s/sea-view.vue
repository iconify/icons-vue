<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="tgx030-6f"/><path class="ipv30fb9o"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:sea-view" /></template>
<style>
.ipv30fb9o {
  d: path("M8.5 11.5a3.5 3.5 0 0 1 7 0Zm-2.5 3q1.5-1.25 3 0t3 0t3 0t3 0M6 18.25q1.5-1.25 3 0t3 0t3 0t3 0");
}

.tgx030-6f {
  d: path("M3 2.5h18v19H3Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
