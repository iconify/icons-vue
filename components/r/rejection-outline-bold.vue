<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="o5r_prbgx"/><path class="bmsk64_re"/><path class="fmv013bbw"/><path class="bxyszcb7e"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:rejection-outline-bold" /></template>
<style>
.bmsk64_re {
  d: path("M9.5 9.5 12 12");
}

.bxyszcb7e {
  d: path("m20 15 -5 5");
}

.fmv013bbw {
  d: path("m15 15 5 5");
}

.o5r_prbgx {
  d: path("M2 5a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

</style>
