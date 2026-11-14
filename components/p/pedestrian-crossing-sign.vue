<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="g6ulkabjn"/><path class="jp_l-zb7a"/><path class="hno6rlq2q"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:pedestrian-crossing-sign" /></template>
<style>
.g6ulkabjn {
  d: path("M2.5 2.5h19v19h-19Z");
}

.hno6rlq2q {
  d: path("m9.5 11.25l2.75-1l2.5 2M7 18.5h3.5m3 0H17");
}

.jp_l-zb7a {
  d: path("M11.5 5.5a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0Zm1 4.25l-1.25 3.75l-2.75 2.25m2.75-2.25L14 15.75");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
