<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ty2spbb9t"/><path class="v-j4yzbct"/><path class="ldscqgc5o"/><path class="vzxh37pxv"/><path class="e99hiubds"/><path class="h3aib2b4u"/><path class="qsabb4b5g"/><path class="dihddo_by"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:swing-duotone-thin" /></template>
<style>
.dihddo_by {
  d: path("M6 18h12");
}

.e99hiubds {
  d: path("M5 3h14");
}

.h3aib2b4u {
  d: path("M8 3v15");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ldscqgc5o {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M16 3v15");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.qsabb4b5g {
  d: path("M16 3v15");
}

.ty2spbb9t {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M5 3h14");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.v-j4yzbct {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M8 3v15");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.vzxh37pxv {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M6 18h12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
