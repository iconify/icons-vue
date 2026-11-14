<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="tole6h7tb"/><path class="qecuhqbrd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:tree-line-duotone" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.qecuhqbrd {
  d: path("M11.9995 16H7.1995C4.3995 16 2.7995 14 3.1995 11.4C3.4995 9.39999 5.1995 8.19989 6.4995 7.79989C6.3995 4.39989 8.7995 2.19989 11.9995 2.19989C15.1995 2.19989 17.5995 4.39989 17.4995 7.79989C18.7995 8.19989 20.4995 9.39999 20.7995 11.4C21.1995 14 19.5995 16 16.7995 16H11.9995Z");
}

.tole6h7tb {
  d: path("M12 21.8V13.6M12 13.6V9.59998M12 13.6L15 10.6M12 13.6L9 10.6M7.5 21.8H16.5");
  opacity: var(--svg-opacity--0-5, 0.5);
}

</style>
