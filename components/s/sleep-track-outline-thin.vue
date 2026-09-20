<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="t3v74kb6y"/><path class="dezc-zb_n"/><path class="dvv2tacko"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:sleep-track-outline-thin" /></template>
<style>
.dezc-zb_n {
  d: path("M2 16.5h20");
}

.dvv2tacko {
  d: path("M13 4a4 4 0 1 0 0 8 3 3 0 0 1 0 -8");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.t3v74kb6y {
  d: path("M2 20v-7h20v7");
}

</style>
