<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="gms_xv68n"/><path class="i7-hwrk0u"/><path class="eogkknb2k"/><path class="r3faxubne"/><path class="ws1d0fbts"/><path class="ylnxs8amf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:safety-check-duotone-thin" /></template>
<style>
.eogkknb2k {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m8 12 2 2 6 -6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.gms_xv68n {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M4 4v16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.i7-hwrk0u {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M20 4v16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.r3faxubne {
  d: path("M4 4v16");
}

.ws1d0fbts {
  d: path("M20 4v16");
}

.ylnxs8amf {
  d: path("m8 12 2 2 6 -6");
}

</style>
