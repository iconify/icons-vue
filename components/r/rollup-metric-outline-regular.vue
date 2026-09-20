<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="r3faxubne"/><path class="oifr9zbpt"/><path class="p4gh801hs"/><path class="qui36tb8q"/><path class="ygselab1a"/><path class="plvacbczu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:rollup-metric-outline-regular" /></template>
<style>
.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.oifr9zbpt {
  d: path("M4 20h16");
}

.p4gh801hs {
  d: path("M8 14v4");
}

.plvacbczu {
  d: path("M18 7v11");
}

.qui36tb8q {
  d: path("M11 12v6");
}

.r3faxubne {
  d: path("M4 4v16");
}

.ygselab1a {
  d: path("M14 15v3");
}

</style>
