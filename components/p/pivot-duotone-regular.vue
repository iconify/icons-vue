<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="s1ajs51ib"/><path class="aqrf9ebcv"/><path class="m905slgxs"/><path class="c7ipi_e1h"/><path class="rqec6t5oj"/><path class="mja2nhbok"/><path class="mg7aqnbsf"/><path class="vhnbtvbtn"/><path class="r5bn6xbek"/><path class="m7-jsbcse"/><path class="rqivuib5z"/><path class="uddzogh0e"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:pivot-duotone-regular" /></template>
<style>
.aqrf9ebcv {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M3 8h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.c7ipi_e1h {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M6 16.5V22");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.m7-jsbcse {
  d: path("M6 16.5V22");
}

.m905slgxs {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m9.5 11 2.5 2.5 2.5 -2.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.mg7aqnbsf {
  d: path("M3 4h18");
}

.mja2nhbok {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M18 16.5V22");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.r5bn6xbek {
  d: path("m9.5 11 2.5 2.5 2.5 -2.5");
}

.rqec6t5oj {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M12 16.5V22");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.rqivuib5z {
  d: path("M12 16.5V22");
}

.s1ajs51ib {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M3 4h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.uddzogh0e {
  d: path("M18 16.5V22");
}

.vhnbtvbtn {
  d: path("M3 8h18");
}

</style>
