<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path clip-rule="evenodd" class="oolq5l6zb"/><path class="fho48pbnt"/><circle class="l2p5rp9gl"/><circle class="mo7_uavfv"/><circle class="e2hurvvfr"/><path class="xof6nn1pj"/><path clip-rule="evenodd" class="wx0apjbfu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:saxophone" /></template>
<style>
.e2hurvvfr {
  cx: 25px;
  cy: 9px;
  r: 2px;
  fill: var(--svg-color--ccd6dd, #ccd6dd);
}

.fho48pbnt {
  fill: var(--svg-color--fdcb58, #fdcb58);
  d: path("M7.5 20C4.04 20 0 18.952 0 16s4.04-4 7.5-4s7.5 1.047 7.5 4c0 2.952-4.04 4-7.5 4");
}

.l2p5rp9gl {
  cx: 19px;
  cy: 17px;
  r: 2px;
  fill: var(--svg-color--ccd6dd, #ccd6dd);
}

.mo7_uavfv {
  cx: 22px;
  cy: 13px;
  r: 2px;
  fill: var(--svg-color--ccd6dd, #ccd6dd);
}

.oolq5l6zb {
  fill: var(--svg-color--fcab40, #fcab40);
  fill-rule: evenodd;
  d: path("M14 16L9 26s-1 2 1 2c1 0 2-2 2-2L26 7s2-4 8-1v2c-3-1-4 1-4 1L15 33s-2 3-7 3c-6 0-7-5-7-8c0-2 1-4 2-6s-2-6-2-6z");
}

.wx0apjbfu {
  fill: var(--svg-color--fcab40, #fcab40);
  fill-rule: evenodd;
  d: path("m8.806 21.703l1.267-1.547l6.19 5.069l-1.267 1.547z");
}

.xof6nn1pj {
  fill: var(--svg-color--9aaab4, #9aaab4);
  d: path("M33.998 10c-.3 0-.605-.068-.893-.211l-2-1a2 2 0 0 1 1.789-3.579l2 1a2 2 0 0 1-.896 3.79");
}

</style>
