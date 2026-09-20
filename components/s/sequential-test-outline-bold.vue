<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="iaj8d8bgd"/><path class="w_4k9q5tv"/><path class="m__qgi9_a"/><path class="nhzanrbsp"/><path class="r8i1ojbwn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:sequential-test-outline-bold" /></template>
<style>
.iaj8d8bgd {
  d: path("m3 8 2 2 3 -3");
}

.m__qgi9_a {
  d: path("m17.5 7 3.5 3.5");
}

.nhzanrbsp {
  d: path("m21 7 -3.5 3.5");
}

.r8i1ojbwn {
  d: path("M3 16.5h18");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.w_4k9q5tv {
  d: path("m10 8 2 2 3 -3");
}

</style>
