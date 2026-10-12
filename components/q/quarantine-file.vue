<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="lt7uwfbtn"/><path class="cd-32esft"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:quarantine-file" /></template>
<style>
.cd-32esft {
  d: path("M10.5 10.25h3m-3 3h3M2.75 6.75v-2a2 2 0 0 1 2-2h2m10.5 0h2a2 2 0 0 1 2 2v2m0 10.5v2a2 2 0 0 1-2 2h-2m-10.5 0h-2a2 2 0 0 1-2-2v-2m7.75-14.5h3m-3 18.5h3M2.75 10.5v3m18.5-3v3");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.lt7uwfbtn {
  width: 8px;
  height: 10.5px;
  x: 8px;
  y: 6.75px;
  rx: 1.5px;
}

</style>
