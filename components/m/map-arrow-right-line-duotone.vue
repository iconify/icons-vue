<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="mmj0m1bao"/><path class="oxw8pabhp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:map-arrow-right-line-duotone" /></template>
<style>
.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.mmj0m1bao {
  d: path("M5.52689 11.9996C5.52689 11.7497 5.4656 11.4998 5.34302 11.2702L2.19099 5.36653C1.45006 3.97878 3.00163 2.49753 4.49746 3.16459L21.0072 10.5271C21.6691 10.8223 22 11.4109 22 11.9996");
}

.oxw8pabhp {
  d: path("M5.52689 11.9997C5.52689 12.2496 5.4656 12.4995 5.34302 12.7291L2.19099 18.6328C1.45006 20.0206 3.00163 21.5018 4.49746 20.8347L21.0072 13.4722C21.6691 13.1771 22 12.5884 22 11.9997");
  opacity: var(--svg-opacity--0-5, 0.5);
}

</style>
