<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="b-bymobfb"/><path class="nog5ftwkf"/><path class="r4bf7ebri"/><circle class="w0f-hlp2t"/><path class="n4kfu5bmh"/><path class="tnljxhbrz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:music-note-slider-linear" /></template>
<style>
.b-bymobfb {
  d: path("M11 22H13C15.8284 22 17.2426 22 18.1213 21.1213C19 20.2426 19 18.8284 19 16V8C19 5.17157 19 3.75736 18.1213 2.87868C17.2426 2 15.8284 2 13 2H11C8.17157 2 6.75736 2 5.87868 2.87868C5 3.75736 5 5.17157 5 8V16C5 18.8284 5 20.2426 5.87868 21.1213C6.75736 22 8.17157 22 11 22Z");
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.n4kfu5bmh {
  d: path("M15 10C13.8954 10 13 9.10457 13 8");
}

.nog5ftwkf {
  d: path("M19 19.5C19.4645 19.5 19.6968 19.5 19.8911 19.4692C20.9608 19.2998 21.7998 18.4608 21.9692 17.3911C22 17.1968 22 16.9645 22 16.5V7.5C22 7.0355 22 6.80325 21.9692 6.60891C21.7998 5.53918 20.9608 4.70021 19.8911 4.53078C19.6968 4.5 19.4645 4.5 19 4.5");
}

.r4bf7ebri {
  d: path("M13 14V11V8");
}

.tnljxhbrz {
  d: path("M5 19.5C4.5355 19.5 4.30325 19.5 4.10891 19.4692C3.03918 19.2998 2.20021 18.4608 2.03078 17.3911C2 17.1968 2 16.9645 2 16.5V7.5C2 7.0355 2 6.80325 2.03078 6.60891C2.20021 5.53918 3.03918 4.70021 4.10891 4.53078C4.30325 4.5 4.5355 4.5 5 4.5");
}

.w0f-hlp2t {
  cx: 11px;
  cy: 14px;
  r: 2px;
}

</style>
