<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="gsjzzm76q"/><path class="o5dbzp2st"/><path class="o6uigcb7l"/><path class="kh0ioebug"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:private-endpoint-duotone-thin" /></template>
<style>
.gsjzzm76q {
  fill: currentColor;
  d: path("M13 14a2 2 0 0 1 2 -2h4a2 2 0 0 1 2 2v3a2 2 0 0 1 -2 2h-4a2 2 0 0 1 -2 -2Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.kh0ioebug {
  d: path("M14 12a3 3 0 0 1 6 0");
}

.o5dbzp2st {
  d: path("m3 3 7 7");
}

.o6uigcb7l {
  d: path("M13 14a2 2 0 0 1 2 -2h4a2 2 0 0 1 2 2v3a2 2 0 0 1 -2 2h-4a2 2 0 0 1 -2 -2Z");
}

</style>
