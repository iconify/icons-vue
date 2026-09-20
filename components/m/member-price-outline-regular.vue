<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="k6fi9qmtq"/><path class="ozi-k-boi"/><path class="qr0eduups"/><path class="fh1okhbsq"/><path class="qzs5rhb5h"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:member-price-outline-regular" /></template>
<style>
.fh1okhbsq {
  d: path("m9 17 6 -6");
}

.k6fi9qmtq {
  d: path("M2 5a2 2 0 0 1 2 -2h16a2 2 0 0 1 2 2v14a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2Z");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.ozi-k-boi {
  d: path("M3 7h18");
}

.qr0eduups {
  d: path("M8.5 11.5a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.qzs5rhb5h {
  d: path("M13.5 16.5a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

</style>
