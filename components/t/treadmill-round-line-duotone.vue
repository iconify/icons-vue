<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><circle class="trr-_mkon"/><path class="xvu4zsr_t"/><path class="a7fuovaen"/><path class="yse-k_tnb"/><path class="csn8e4bgx"/><path class="q0799i8_d"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:treadmill-round-line-duotone" /></template>
<style>
.a7fuovaen {
  d: path("M3 15.5H3.37868C4.73694 15.5 6.03957 14.9604 7 14");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.csn8e4bgx {
  stroke-linejoin: round;
  d: path("M19.4888 22H3.08684C2.48659 22 2 21.5134 2 20.9131C2 20.3852 2.37943 19.9336 2.89949 19.8426L19.0559 17.0152C20.5926 16.7463 22 17.9288 22 19.4888C22 20.8757 20.8757 22 19.4888 22Z");
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.q0799i8_d {
  stroke-linejoin: round;
  d: path("M18.0469 17.1852L19.1215 10.0213C19.3484 8.50835 20.4995 7.30003 21.9997 7");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.trr-_mkon {
  cx: 15px;
  cy: 4px;
  r: 2px;
}

.xvu4zsr_t {
  d: path("M11 16V15.0262C11 14.9077 11 14.8484 10.9979 14.7918C10.9672 13.981 10.6095 13.2172 10.0062 12.6746C9.96408 12.6367 9.91852 12.5987 9.8275 12.5229C9.69411 12.4117 9.62741 12.3561 9.5758 12.3065C8.80944 11.5687 8.75462 10.3602 9.45104 9.55618C9.49795 9.50202 9.55934 9.44063 9.68211 9.31785L10.0113 8.98862C10.9639 8.0361 10.6532 6.42275 9.41502 5.89212C8.84181 5.64646 8.18464 5.69706 7.65581 6.02759L4.5 7.99997");
}

.yse-k_tnb {
  d: path("M12.5 10C13.4737 10.3246 14.5263 10.3246 15.5 10");
  opacity: var(--svg-opacity--0-5, 0.5);
}

</style>
