<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ak-925b-h"/><rect class="of5y5gb5u"/><path class="kchxn6byl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:niqab" /></template>
<style>
.ak-925b-h {
  d: path("M3 21.25c0-3.75 2-5.75 4-6.5C5.75 13 5.25 11 5.25 9.5a6.75 6.75 0 0 1 13.5 0c0 1.5-.5 3.5-1.75 5.25c2 .75 4 2.75 4 6.5Z");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.kchxn6byl {
  d: path("M8.75 15c2.25 1 4.25 1 6.5 0m-6.5 3.25c2.25 1 4.25 1 6.5 0");
}

.of5y5gb5u {
  width: 8px;
  height: 3.75px;
  x: 8px;
  y: 7.75px;
  rx: 1.75px;
}

</style>
