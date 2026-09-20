<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="ugh6y_a-z"/><path class="ixfun3jnw"/><path class="bqauhbcsv"/><path class="mcubrkb2y"/><path class="gjjx1zbjy"/><path class="a5c-jhmhz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:transfer-failed-duotone-bold" /></template>
<style>
.a5c-jhmhz {
  d: path("m14 13 -4 4");
}

.bqauhbcsv {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m14 13 -4 4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.gjjx1zbjy {
  d: path("m10 13 4 4");
}

.ixfun3jnw {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m10 13 4 4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.mcubrkb2y {
  d: path("M2 21h20M5 21V9m14 12V9M2 9h20M5 9l5.5 -5.5h3L19 9");
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

</style>
