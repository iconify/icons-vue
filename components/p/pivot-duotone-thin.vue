<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="r0_oskb4z"/><path class="s9jzbjbwv"/><path class="isqavccwq"/><path class="dfsqwi14v"/><path class="lp-t2ybaz"/><path class="rb26kqbwl"/><path class="mg7aqnbsf"/><path class="vhnbtvbtn"/><path class="r5bn6xbek"/><path class="m7-jsbcse"/><path class="rqivuib5z"/><path class="uddzogh0e"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:pivot-duotone-thin" /></template>
<style>
.dfsqwi14v {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M6 16.5V22");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.isqavccwq {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m9.5 11 2.5 2.5 2.5 -2.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.lp-t2ybaz {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M12 16.5V22");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.m7-jsbcse {
  d: path("M6 16.5V22");
}

.mg7aqnbsf {
  d: path("M3 4h18");
}

.r0_oskb4z {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 4h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.r5bn6xbek {
  d: path("m9.5 11 2.5 2.5 2.5 -2.5");
}

.rb26kqbwl {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M18 16.5V22");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.rqivuib5z {
  d: path("M12 16.5V22");
}

.s9jzbjbwv {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 8h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.uddzogh0e {
  d: path("M18 16.5V22");
}

.vhnbtvbtn {
  d: path("M3 8h18");
}

</style>
