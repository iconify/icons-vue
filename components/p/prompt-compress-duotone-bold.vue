<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="q7zfvpbhn"/><path class="qz9_3ub7s"/><path class="eyr16rboh"/><path class="o9puxe-xe"/><path class="v9il_wb-q"/><path class="dznv025mt"/><path class="edr2cqsrt"/><path class="sz5hq9bxf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:prompt-compress-duotone-bold" /></template>
<style>
.dznv025mt {
  d: path("M6 14h12");
}

.edr2cqsrt {
  d: path("M9.5 3 12 5.5 14.5 3");
}

.eyr16rboh {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M9.5 3 12 5.5 14.5 3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.o9puxe-xe {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m9.5 21 2.5 -2.5 2.5 2.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.q7zfvpbhn {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M6 10h12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.qz9_3ub7s {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M6 14h12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.sz5hq9bxf {
  d: path("m9.5 21 2.5 -2.5 2.5 2.5");
}

.v9il_wb-q {
  d: path("M6 10h12");
}

</style>
