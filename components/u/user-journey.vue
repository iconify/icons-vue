<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><circle class="tdjjhsyrl"/><path class="l0lugdc2g"/><path class="tai7-ubtf"/><path class="roc9-cbpd"/><path class="eooj7sbat"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:user-journey" /></template>
<style>
.eooj7sbat {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M16.5 19.5h.01");
}

.l0lugdc2g {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12.5 16h8a.5.5 0 0 0 .5-.5c0-2-2-3-4.5-3s-4.5 1-4.5 3a.5.5 0 0 0 .5.5");
}

.roc9-cbpd {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.5 7v3.25a2.25 2.25 0 0 0 2.25 2.25h.5a2.25 2.25 0 0 1 2.25 2.25v2.5a2.25 2.25 0 0 0 2.25 2.25H14");
}

.tai7-ubtf {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M4.5 4.5h.01");
}

.tdjjhsyrl {
  cx: 16.5px;
  cy: 7px;
  r: 2.75px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
