<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="edllzuogn"/><path class="iaozfqbuj"/><path class="tuv2qrbve"/><path class="z28ycwbis"/><path class="cjc0mqb2o"/><path class="z6ec0ccup"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:model-swap-duotone-bold" /></template>
<style>
.cjc0mqb2o {
  d: path("M9 14h7");
}

.edllzuogn {
  fill: currentColor;
  d: path("M14.5 4H17a3 3 0 0 1 3 3v10a3 3 0 0 1 -3 3H7a3 3 0 0 1 -3 -3V8l4 -4h2.5");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.iaozfqbuj {
  d: path("M14.5 4H17a3 3 0 0 1 3 3v10a3 3 0 0 1 -3 3H7a3 3 0 0 1 -3 -3V8l4 -4h2.5");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.tuv2qrbve {
  d: path("M8 10h7");
}

.z28ycwbis {
  d: path("m13 8 2 2 -2 2");
}

.z6ec0ccup {
  d: path("m11 12 -2 2 2 2");
}

</style>
