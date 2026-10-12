<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="cudzonb3z"/><path class="mmd8_bz_i"/><path class="iu0eyvbsb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:toast-sharp" /></template>
<style>
.cudzonb3z {
  d: path("M5 21h15v-9.75l1.25-1.103V8.25c0-2.1-1.65-3.5-3.75-3.5h-11c-2.1 0-3.75 1.4-3.75 3.5v1.897L4 11.25V21z");
}

.iu0eyvbsb {
  d: path("m11.22 10.96l2.21.39l.74.13l-.13.74l-.39 2.21l-.13.74l-.74-.13l-2.21-.39l-.74-.13l.13-.74l.39-2.21l.13-.74z");
}

.mmd8_bz_i {
  d: path("M7 18h10v-7l1.25-.694V7.75H5.75v2.556L7 11Z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
