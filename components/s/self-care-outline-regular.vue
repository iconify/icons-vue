<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="d88esignp"/><path class="nl66y9men"/><path class="f4b4cfbbo"/><path class="x-ycuabua"/><path class="i6okezb6k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:self-care-outline-regular" /></template>
<style>
.d88esignp {
  d: path("M8 13h8v8H8Z");
}

.f4b4cfbbo {
  d: path("M12 13V8");
}

.i6okezb6k {
  d: path("M12 8c0 -3 3 -5 7 -5 0 3 -3 5 -7 5");
}

.nl66y9men {
  d: path("M6 16h12");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.x-ycuabua {
  d: path("M12 8c0 -4 -3 -6 -7 -6 0 4 3 6 7 6");
}

</style>
