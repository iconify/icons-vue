<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="edllzuogn"/><path class="sgm8b3bpu"/><path class="ffk2gcbgz"/><path class="sr5onmy8p"/><path class="iaozfqbuj"/><path class="styxdpaok"/><path class="mvtotuz5f"/><path class="dfnxhglsm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:runner-pool-duotone-thin" /></template>
<style>
.dfnxhglsm {
  d: path("M13.5 14a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.edllzuogn {
  fill: currentColor;
  d: path("M14.5 4H17a3 3 0 0 1 3 3v10a3 3 0 0 1 -3 3H7a3 3 0 0 1 -3 -3V8l4 -4h2.5");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.ffk2gcbgz {
  fill: currentColor;
  d: path("M8.5 14a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.iaozfqbuj {
  d: path("M14.5 4H17a3 3 0 0 1 3 3v10a3 3 0 0 1 -3 3H7a3 3 0 0 1 -3 -3V8l4 -4h2.5");
}

.mvtotuz5f {
  d: path("M8.5 14a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.sgm8b3bpu {
  fill: currentColor;
  d: path("M11 9.5a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.sr5onmy8p {
  fill: currentColor;
  d: path("M13.5 14a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.styxdpaok {
  d: path("M11 9.5a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

</style>
