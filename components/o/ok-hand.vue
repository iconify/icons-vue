<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="j00-kub2g"/><circle class="lc9ede9dj"/><path class="ntcsy005u"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:ok-hand" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.j00-kub2g {
  d: path("M12.25 8.75v-3.5a1.25 1.25 0 0 1 2.5 0V5a1.25 1.25 0 0 1 2.5 0v2.5a1.15 1.15 0 0 1 2.3 0V15a6.25 6.25 0 0 1-6.25 6.25h-.5A5.25 5.25 0 0 1 7.5 16v-1.12a4.25 4.25 0 1 1 4.75-6.13");
}

.lc9ede9dj {
  cx: 8.5px;
  cy: 10.75px;
  r: 1.75px;
}

.ntcsy005u {
  d: path("M14.75 5.5v6m2.5-4V12");
}

</style>
