<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="zn5vtx2pl"/><path class="smpt-2ntk"/><path class="is8nqnbzt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:patch-update" /></template>
<style>
.is8nqnbzt {
  d: path("M16.75 14.5L18 15.75L16.75 17");
}

.smpt-2ntk {
  d: path("M5.464 9L9 5.464L12.536 9L9 12.536Zm15.286 9.5A2.75 2.75 0 1 1 18 15.75");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.zn5vtx2pl {
  d: path("m2.99 10.768l7.778-7.778a1 1 0 0 1 1.414 0l2.828 2.828a1 1 0 0 1 0 1.414L7.232 15.01a1 1 0 0 1-1.414 0L2.99 12.182a1 1 0 0 1 0-1.414Z");
}

</style>
