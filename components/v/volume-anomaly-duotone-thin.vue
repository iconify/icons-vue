<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="b3figj0_h"/><path class="i-2uxcc_i"/><path class="e8dcyvi8e"/><path class="mqwe1qbas"/><path class="hi99_8zvm"/><path class="ior14cbcm"/><path class="vezho9b5g"/><path class="ul-6megvv"/><path class="hb39b-bug"/><path class="lqktbo2ou"/><path class="ejc7sbawl"/><path class="z9ittvbis"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:volume-anomaly-duotone-thin" /></template>
<style>
.b3figj0_h {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M4 14v5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.e8dcyvi8e {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M12 3v16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.ejc7sbawl {
  d: path("M20 15v4");
}

.hb39b-bug {
  d: path("M12 3v16");
}

.hi99_8zvm {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M20 15v4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.i-2uxcc_i {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M8 11v8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.ior14cbcm {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M2 19h20");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.lqktbo2ou {
  d: path("M16 12v7");
}

.mqwe1qbas {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M16 12v7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.ul-6megvv {
  d: path("M8 11v8");
}

.vezho9b5g {
  d: path("M4 14v5");
}

.z9ittvbis {
  d: path("M2 19h20");
}

</style>
