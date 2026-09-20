<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="mg7aqnbsf"/><path class="j835zw5-z"/><path class="rkhcgsbdl"/><path class="ix782hbkz"/><path class="eylqpv51p"/><path class="ktzvm-xej"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:synthetic-row-outline-bold" /></template>
<style>
.eylqpv51p {
  d: path("M11 14a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.ix782hbkz {
  d: path("M5 14a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.j835zw5-z {
  d: path("M3 9h18");
}

.ktzvm-xej {
  d: path("M17 14a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.mg7aqnbsf {
  d: path("M3 4h18");
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

</style>
