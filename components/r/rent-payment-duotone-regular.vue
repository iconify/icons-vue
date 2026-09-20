<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="wvt4g8bjb"/><path class="a6e_o0bju"/><path class="dvfmj91gv"/><path class="r9il7jbjw"/><path class="gzes1rhcl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:rent-payment-duotone-regular" /></template>
<style>
.a6e_o0bju {
  d: path("m3 11 9 -9 9 9");
}

.dvfmj91gv {
  d: path("M6 11v10h12V11");
}

.gzes1rhcl {
  d: path("M12 13.5v4");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.r9il7jbjw {
  d: path("M9 15.5a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

.wvt4g8bjb {
  fill: currentColor;
  d: path("M9 15.5a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
