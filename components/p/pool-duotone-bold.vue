<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="khwz-2uwv"/><path class="q7fzex61h"/><path class="xa9vorq4l"/><path class="szg40d_7w"/><path class="eoz5n0suo"/><path class="bod4n0b3z"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:pool-duotone-bold" /></template>
<style>
.bod4n0b3z {
  d: path("M2 18h20");
}

.eoz5n0suo {
  d: path("m4 11 2.5 -2.5L9 11l2.5 -2.5L14 11l2.5 -2.5L19 11");
}

.khwz-2uwv {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M2 7v8h20V7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.q7fzex61h {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m4 11 2.5 -2.5L9 11l2.5 -2.5L14 11l2.5 -2.5L19 11");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.szg40d_7w {
  d: path("M2 7v8h20V7");
}

.xa9vorq4l {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M2 18h20");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
