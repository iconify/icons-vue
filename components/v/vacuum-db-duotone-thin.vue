<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="r0_oskb4z"/><path class="s9jzbjbwv"/><path class="enu3nubgv"/><path class="z8yjphbma"/><path class="cupnz1b-s"/><path class="mg7aqnbsf"/><path class="vhnbtvbtn"/><path class="t0-mwc0xy"/><path class="o3x_gzblq"/><path class="qik8460ao"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:vacuum-db-duotone-thin" /></template>
<style>
.cupnz1b-s {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M5 21h14");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.enu3nubgv {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M12 10v6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.mg7aqnbsf {
  d: path("M3 4h18");
}

.o3x_gzblq {
  d: path("m8 13 4 4 4 -4");
}

.qik8460ao {
  d: path("M5 21h14");
}

.r0_oskb4z {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 4h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.s9jzbjbwv {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 8h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.t0-mwc0xy {
  d: path("M12 10v6");
}

.vhnbtvbtn {
  d: path("M3 8h18");
}

.z8yjphbma {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m8 13 4 4 4 -4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
