<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="tn6npxrqt"/><path class="vo3bhyoeg"/><path class="uvrxvrzpu"/><path class="o8zcug1ct"/><path class="jelyk0_mp"/><path class="b64bcebht"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:motorbike-duotone-bold" /></template>
<style>
.b64bcebht {
  d: path("m9.5 11 3 -3h4");
}

.jelyk0_mp {
  d: path("M5.5 14.5 9 11h6l3.5 3.5");
}

.o8zcug1ct {
  d: path("M15 14.5a3.5 3.5 0 1 0 7 0 3.5 3.5 0 1 0 -7 0");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.tn6npxrqt {
  fill: currentColor;
  d: path("M2 14.5a3.5 3.5 0 1 0 7 0 3.5 3.5 0 1 0 -7 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.uvrxvrzpu {
  d: path("M2 14.5a3.5 3.5 0 1 0 7 0 3.5 3.5 0 1 0 -7 0");
}

.vo3bhyoeg {
  fill: currentColor;
  d: path("M15 14.5a3.5 3.5 0 1 0 7 0 3.5 3.5 0 1 0 -7 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
