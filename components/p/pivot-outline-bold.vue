<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="mg7aqnbsf"/><path class="vhnbtvbtn"/><path class="r5bn6xbek"/><path class="m7-jsbcse"/><path class="rqivuib5z"/><path class="uddzogh0e"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:pivot-outline-bold" /></template>
<style>
.m7-jsbcse {
  d: path("M6 16.5V22");
}

.mg7aqnbsf {
  d: path("M3 4h18");
}

.r5bn6xbek {
  d: path("m9.5 11 2.5 2.5 2.5 -2.5");
}

.rqivuib5z {
  d: path("M12 16.5V22");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.uddzogh0e {
  d: path("M18 16.5V22");
}

.vhnbtvbtn {
  d: path("M3 8h18");
}

</style>
