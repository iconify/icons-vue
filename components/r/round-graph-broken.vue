<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="qfxoisp8j"/><path class="q2k_pybqv"/><path class="a09g2ehcd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:round-graph-broken" /></template>
<style>
.a09g2ehcd {
  d: path("M12 16C14.2091 16 16 14.2091 16 12C16 9.79086 14.2091 8 12 8");
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.q2k_pybqv {
  d: path("M12 5C15.866 5 19 8.13401 19 12C19 15.866 15.866 19 12 19C10.9264 19 9.90926 18.7583 9 18.3264M6.25469 16C5.46381 14.8662 5 13.4872 5 12");
}

.qfxoisp8j {
  d: path("M12 2C17.5228 2 22 6.47715 22 12C22 13.8214 21.513 15.5291 20.6622 17M5 4.85857C3.14864 6.67349 2 9.20261 2 12C2 17.5228 6.47715 22 12 22C13.8214 22 15.5291 21.513 17 20.6622");
}

</style>
