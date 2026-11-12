<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><circle class="v90gbqbox"/><path class="lq7a-_8su"/><path class="pq5xj2bli"/><path class="qi4ad9bta"/><path class="i0kw3he6n"/><path class="n_ucwybmv"/><path class="t9jxz8b5u"/><path class="tljtj2ber"/><path class="uq9j8rbvn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:sun-line-duotone" /></template>
<style>
.i0kw3he6n {
  d: path("M3 12L2 12");
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.lq7a-_8su {
  d: path("M12 2V3");
}

.n_ucwybmv {
  d: path("M19.0703 4.9292L18.6775 5.32204");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.pq5xj2bli {
  d: path("M12 21V22");
}

.qi4ad9bta {
  d: path("M22 12L21 12");
}

.t9jxz8b5u {
  d: path("M5.32227 18.6782L4.92943 19.0711");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.tljtj2ber {
  d: path("M19.0703 19.0708L18.6775 18.678");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.uq9j8rbvn {
  d: path("M5.32227 5.32178L4.92943 4.92894");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.v90gbqbox {
  cx: 12px;
  cy: 12px;
  r: 6px;
}

</style>
