<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="yef0r6syg"/><path class="rkid2r5ui"/><path class="ab_oogw8h"/><path class="z9_55xbmv"/><path class="uba9drbfr"/><path class="y5rmlnoay"/><path class="nhri7pb9i"/><path class="gsl5knvuq"/><path class="xa52mrrsy"/><path class="e5d_yrbyo"/><path class="z82iob5ig"/><path class="q9naw_b2m"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:mist-duotone-thin" /></template>
<style>
.ab_oogw8h {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 13h6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.e5d_yrbyo {
  d: path("M12 13h9");
}

.gsl5knvuq {
  d: path("M15 8h6");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.nhri7pb9i {
  d: path("M3 8h9");
}

.q9naw_b2m {
  d: path("M17 18h4");
}

.rkid2r5ui {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M15 8h6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.uba9drbfr {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M5 18h9");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.xa52mrrsy {
  d: path("M3 13h6");
}

.y5rmlnoay {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M17 18h4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.yef0r6syg {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 8h9");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.z82iob5ig {
  d: path("M5 18h9");
}

.z9_55xbmv {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M12 13h9");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
