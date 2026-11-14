<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="j2m37yb5l"/><path class="arhpmczqt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:sprint-demo" /></template>
<style>
.arhpmczqt {
  d: path("m10 6l5.75 3.75L10 13.5Zm0 10.5L9 21m5-4.5l1 4.5m-7.5 0h9");
}

.j2m37yb5l {
  d: path("M2.5 3h19v13.5h-19Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
