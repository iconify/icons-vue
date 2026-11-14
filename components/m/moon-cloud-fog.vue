<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ymlh1hb_d"/><path class="d9l-n1b1c"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:moon-cloud-fog" /></template>
<style>
.d9l-n1b1c {
  d: path("M12.75 5.5a3.5 3.5 0 1 1 4.5 4a4.5 4.5 0 0 0-4.5-4M4 17.5h12M7.5 21h12");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ymlh1hb_d {
  d: path("M6.5 14a3.5 3.5 0 0 1 .25-7a4.5 4.5 0 0 1 8 .75A3.25 3.25 0 0 1 15.5 14Z");
}

</style>
