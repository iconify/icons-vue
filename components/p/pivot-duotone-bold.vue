<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="aqn8oeb4o"/><path class="nu0ti3ggl"/><path class="bcbymgbja"/><path class="ggwf6pb4g"/><path class="cy12f-blm"/><path class="mfn36501g"/><path class="mg7aqnbsf"/><path class="vhnbtvbtn"/><path class="r5bn6xbek"/><path class="m7-jsbcse"/><path class="rqivuib5z"/><path class="uddzogh0e"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:pivot-duotone-bold" /></template>
<style>
.aqn8oeb4o {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M3 4h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.bcbymgbja {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m9.5 11 2.5 2.5 2.5 -2.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.cy12f-blm {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M12 16.5V22");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.ggwf6pb4g {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M6 16.5V22");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.m7-jsbcse {
  d: path("M6 16.5V22");
}

.mfn36501g {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M18 16.5V22");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.mg7aqnbsf {
  d: path("M3 4h18");
}

.nu0ti3ggl {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M3 8h18");
  opacity: var(--svg-opacity--0-2, 0.2);
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
