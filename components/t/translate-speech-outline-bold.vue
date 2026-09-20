<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="g8q62k13p"/><path class="n49oq7__n"/><path class="m99qwmbqy"/><path class="kt4vswbcx"/><path class="u9ungwb-f"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:translate-speech-outline-bold" /></template>
<style>
.g8q62k13p {
  d: path("M5.88 14.12a3 3 0 0 1 0 -4.24");
}

.kt4vswbcx {
  d: path("M18.12 9.88a3 3 0 0 1 0 4.24");
}

.m99qwmbqy {
  d: path("M11.5 9.5 14 12l-2.5 2.5");
}

.n49oq7__n {
  d: path("M3.76 16.24a6 6 0 0 1 0 -8.5");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.u9ungwb-f {
  d: path("M20.24 7.76a6 6 0 0 1 0 8.5");
}

</style>
