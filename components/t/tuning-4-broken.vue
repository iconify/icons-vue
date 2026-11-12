<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="uor89vbsf"/><path class="gtac9dspq"/><path class="vqm0q2-3k"/><path class="r62upcntk"/><path class="hrnfiobgn"/><path class="q9ut4vb6h"/><path class="af0dr8b1w"/><path class="eolqirc7p"/><path class="oapmu3bsb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:tuning-4-broken" /></template>
<style>
.af0dr8b1w {
  d: path("M19 4H16");
}

.eolqirc7p {
  d: path("M5 20H7.66667");
}

.gtac9dspq {
  d: path("M14 6C12.8954 6 12 5.10457 12 4C12 2.89543 12.8954 2 14 2C15.1046 2 16 2.89543 16 4C16 5.10457 15.1046 6 14 6Z");
}

.hrnfiobgn {
  d: path("M6.5 4H5M12 4H9.25");
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.oapmu3bsb {
  d: path("M10 12H7.5M5.5 12H5");
}

.q9ut4vb6h {
  d: path("M19 12H14");
}

.r62upcntk {
  d: path("M17.5 20H19M12 20H14.75");
}

.uor89vbsf {
  d: path("M12 14C10.8954 14 10 13.1046 10 12C10 10.8954 10.8954 10 12 10C13.1046 10 14 10.8954 14 12C14 13.1046 13.1046 14 12 14Z");
}

.vqm0q2-3k {
  d: path("M10 22C11.1046 22 12 21.1046 12 20C12 18.8954 11.1046 18 10 18C8.89543 18 8 18.8954 8 20C8 21.1046 8.89543 22 10 22Z");
}

</style>
