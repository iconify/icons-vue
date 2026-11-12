<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="lyac2jmak"/><path class="zavg8bcsl"/><path class="kancj-buo"/><path class="r60x9s_xf"/><path class="io9xp6bva"/><path class="sowea2b_e"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:tuning-2-line-duotone" /></template>
<style>
.io9xp6bva {
  d: path("M2 17H6");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.kancj-buo {
  d: path("M13 17H22");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.lyac2jmak {
  d: path("M9.5 14C11.1569 14 12.5 15.3431 12.5 17C12.5 18.6568 11.1569 20 9.5 20C7.84315 20 6.5 18.6568 6.5 17C6.5 15.3431 7.84315 14 9.5 14Z");
}

.r60x9s_xf {
  d: path("M11 7L2 6.9585");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.sowea2b_e {
  d: path("M22 7H18");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.zavg8bcsl {
  d: path("M14.5 3.99998C12.8431 3.99998 11.5 5.34312 11.5 6.99998C11.5 8.65683 12.8431 9.99998 14.5 9.99998C16.1569 9.99998 17.5 8.65683 17.5 6.99998C17.5 5.34312 16.1569 3.99998 14.5 3.99998Z");
}

</style>
