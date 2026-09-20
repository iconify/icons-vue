<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="ky7fjq4zo"/><path class="n939_wb7j"/><path class="pi2myqzrv"/><path class="ra_mgw2ph"/><path class="tfnum6bjl"/><path class="z55just5o"/><path class="b4373m80b"/><path class="ryzx2-jfe"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:subquestion-duotone-regular" /></template>
<style>
.b4373m80b {
  d: path("M14.5 13.5A2.5 2.5 0 1 1 17 16");
}

.ky7fjq4zo {
  fill: currentColor;
  d: path("M7 15.5a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.n939_wb7j {
  fill: currentColor;
  d: path("M16 19.5a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.pi2myqzrv {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M4 7a4 4 0 1 1 4 4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.ra_mgw2ph {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M14.5 13.5A2.5 2.5 0 1 1 17 16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.ryzx2-jfe {
  d: path("M16 19.5a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.tfnum6bjl {
  d: path("M4 7a4 4 0 1 1 4 4");
}

.z55just5o {
  d: path("M7 15.5a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

</style>
