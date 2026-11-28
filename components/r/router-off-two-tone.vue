<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="wkfai5bic"/><path class="qpxaerbvm"/><path clip-rule="evenodd" class="qirn56blw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:router-off-two-tone" /></template>
<style>
.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.qirn56blw {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M9 16C9 16.5523 8.5523 17 8 17C7.4477 17 7 16.5523 7 16C7 15.4477 7.4477 15 8 15C8.5523 15 9 15.4477 9 16Z");
  stroke: none;
}

.qpxaerbvm {
  d: path("M20 20H4C2.8954 20 2 19.1046 2 18V14C2 12.8954 2.8954 12 4 12H12M7 12L5.3333 5.3333M2 2L22 22");
}

.wkfai5bic {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M20.8715 20.8715C20.5957 20.9551 20.3031 21 20 21H4C2.3431 21 1 19.6569 1 18V14C1 12.3431 2.3431 11 4 11H11L20.8715 20.8715ZM16.4172 12.1746C16.1823 11.9345 16.0739 11.5818 16.1613 11.232L18.0299 3.7575C18.1638 3.2217 18.7067 2.8959 19.2425 3.0299C19.7783 3.1638 20.1041 3.7067 19.9701 4.2425L18.2807 11H20C21.6569 11 23 12.3431 23 14V16.3431C23 16.8954 22.5523 17.3431 22 17.3431C21.7239 17.3431 21.4739 17.2312 21.2929 17.0502L16.9498 12.7071C16.8604 12.6178 16.7879 12.5116 16.7374 12.3937C16.6148 12.3413 16.5068 12.2662 16.4172 12.1746Z");
  stroke: none;
}

</style>
