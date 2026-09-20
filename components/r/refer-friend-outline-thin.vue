<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="paopftbkn"/><path class="k-733g5om"/><path class="rau56wyhw"/><path class="xubklhs8n"/><path class="vylmt4x9b"/><path class="l59qyvblu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:refer-friend-outline-thin" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.k-733g5om {
  d: path("M2 19.5a4 4 0 0 1 8 0");
}

.l59qyvblu {
  d: path("m11.5 9.5 2 2 -2 2");
}

.paopftbkn {
  d: path("M3 5.5a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

.rau56wyhw {
  d: path("M15 5.5a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

.vylmt4x9b {
  d: path("M9.5 11.5h4");
}

.xubklhs8n {
  d: path("M14 19.5a4 4 0 0 1 8 0");
}

</style>
