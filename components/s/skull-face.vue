<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="n5vyofxgs"/><circle class="fwf1xiw5o"/><circle class="aez0w84lj"/><path class="gc_8f121e"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:skull-face" /></template>
<style>
.aez0w84lj {
  cx: 14.75px;
  cy: 10.25px;
  r: 1.75px;
}

.fwf1xiw5o {
  cx: 9.25px;
  cy: 10.25px;
  r: 1.75px;
}

.gc_8f121e {
  d: path("M12 13v1m-1.5 4v3.25m3-3.25v3.25");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.n5vyofxgs {
  d: path("M12 2.75c4.4 0 7.75 3 7.75 7.25c0 2.4-1 4.2-2.75 5.25v4.5a1.5 1.5 0 0 1-1.5 1.5h-7a1.5 1.5 0 0 1-1.5-1.5v-4.5C5.25 14.2 4.25 12.4 4.25 10c0-4.25 3.35-7.25 7.75-7.25");
}

</style>
