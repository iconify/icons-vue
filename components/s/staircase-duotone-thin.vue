<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="s6ckx-bvr"/><path class="ymhw07_9a"/><path class="sb40gqbga"/><path class="bos0j4biy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:staircase-duotone-thin" /></template>
<style>
.bos0j4biy {
  d: path("M3 21h18");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.s6ckx-bvr {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 21v-4h5v-4h5V9h5V5h3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.sb40gqbga {
  d: path("M3 21v-4h5v-4h5V9h5V5h3");
}

.ymhw07_9a {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 21h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
