<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="znfuzdoyp"/><path class="hfzq5f4-k"/><path class="l_69zfb0c"/><path class="rkhcgsbdl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:metal-detecting-outline-bold" /></template>
<style>
.hfzq5f4-k {
  d: path("M7 9h6");
}

.l_69zfb0c {
  d: path("M9 13a4 4 0 1 0 8 0 4 4 0 1 0 -8 0");
}

.rkhcgsbdl {
  d: path("M3 19h18");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.znfuzdoyp {
  d: path("M7 3v6");
}

</style>
