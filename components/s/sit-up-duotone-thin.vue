<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="bq9mex9td"/><path class="neabk9byu"/><path class="ctc9ejfah"/><path class="ycakidrmo"/><path class="bod4n0b3z"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:sit-up-duotone-thin" /></template>
<style>
.bod4n0b3z {
  d: path("M2 18h20");
}

.bq9mex9td {
  fill: currentColor;
  d: path("M2 7a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.ctc9ejfah {
  d: path("m8 10 5 5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.neabk9byu {
  d: path("M2 7a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

.ycakidrmo {
  d: path("m13 15 4 -4 4 4");
}

</style>
