<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="tg5bh2bez"/><path class="tuk2cgbpz"/><path class="c0_st1wwk"/><path class="ilcfk6b1a"/><path class="ils7yp4cg"/><path class="bv1y61bvs"/><path class="us2evabuy"/><path class="qw7b_6b1t"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:room-service-duotone-regular" /></template>
<style>
.bv1y61bvs {
  d: path("M4 16a8 8 0 0 1 16 0");
}

.c0_st1wwk {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M12 5.5V8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.ilcfk6b1a {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M8 20h8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.ils7yp4cg {
  d: path("M2 16h20");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.qw7b_6b1t {
  d: path("M8 20h8");
}

.tg5bh2bez {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M2 16h20");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.tuk2cgbpz {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M4 16a8 8 0 0 1 16 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.us2evabuy {
  d: path("M12 5.5V8");
}

</style>
