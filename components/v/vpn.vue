<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="btrj1hi8t"/><path class="h6e9_k1gn"/><path class="ct8a2lsay"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:vpn" /></template>
<style>
.btrj1hi8t {
  d: path("M2.75 21.25V12a9.25 9.25 0 0 1 18.5 0v9.25m-18.5 0h18.5");
}

.ct8a2lsay {
  d: path("M12 13.25a1.25 1.25 0 1 1 0 2.5a1.25 1.25 0 0 1 0-2.5m0 2.5v2");
}

.h6e9_k1gn {
  d: path("M7.5 21.25V13a4.5 4.5 0 0 1 9 0v8.25Z");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
