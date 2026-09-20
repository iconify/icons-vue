<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="r0_oskb4z"/><path class="epwe3rblo"/><path class="uk8vb-m2y"/><path class="bt_2bvgpa"/><path class="hdist0u2z"/><path class="mg7aqnbsf"/><path class="j835zw5-z"/><path class="en0j5saud"/><path class="rkhcgsbdl"/><path class="nk7549ffs"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:unused-export-duotone-thin" /></template>
<style>
.bt_2bvgpa {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 19h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.en0j5saud {
  d: path("M3 14h12");
}

.epwe3rblo {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 9h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.hdist0u2z {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m7 16.5 5 -5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.j835zw5-z {
  d: path("M3 9h18");
}

.mg7aqnbsf {
  d: path("M3 4h18");
}

.nk7549ffs {
  d: path("m7 16.5 5 -5");
}

.r0_oskb4z {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 4h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.rkhcgsbdl {
  d: path("M3 19h18");
}

.uk8vb-m2y {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 14h12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
