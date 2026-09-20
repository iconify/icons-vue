<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="l5ji9nb1h"/><path class="y6d6ymb5v"/><path class="zbe_bibfe"/><path class="filuri95n"/><path class="p9fnnqwai"/><path class="g7rxpleju"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:wind-chill-duotone-bold" /></template>
<style>
.filuri95n {
  d: path("M8 4v8m-4 0 8 -8");
}

.g7rxpleju {
  d: path("M4 20h14");
}

.l5ji9nb1h {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M8 4v8m-4 0 8 -8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.p9fnnqwai {
  d: path("M4 16h11a3 3 0 1 1 -3 3");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.y6d6ymb5v {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M4 16h11a3 3 0 1 1 -3 3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.zbe_bibfe {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M4 20h14");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
