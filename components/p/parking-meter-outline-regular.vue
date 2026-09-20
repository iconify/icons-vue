<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="kacaq8-ee"/><path class="o2i86qb_j"/><path class="uadefenvd"/><path class="qr1iqpomq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:parking-meter-outline-regular" /></template>
<style>
.kacaq8-ee {
  d: path("M5 4a2 2 0 0 1 2 -2h10a2 2 0 0 1 2 2v8a2 2 0 0 1 -2 2H7a2 2 0 0 1 -2 -2Z");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.o2i86qb_j {
  d: path("M12 14v8");
}

.qr1iqpomq {
  d: path("M9 8h6");
}

.uadefenvd {
  d: path("M7 22h10");
}

</style>
