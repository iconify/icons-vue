<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="ugh6y_a-z"/><path class="x7bej-kge"/><path class="mcubrkb2y"/><path class="nfut05pyf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:savings-account-duotone-bold" /></template>
<style>
.mcubrkb2y {
  d: path("M2 21h20M5 21V9m14 12V9M2 9h20M5 9l5.5 -5.5h3L19 9");
}

.nfut05pyf {
  d: path("m9 18 2 -2 2 2 2 -2");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.ugh6y_a-z {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M2 21h20M5 21V9m14 12V9M2 9h20M5 9l5.5 -5.5h3L19 9");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.x7bej-kge {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m9 18 2 -2 2 2 2 -2");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
