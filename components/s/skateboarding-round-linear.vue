<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="bahctlbqr"/><circle class="pyd8uurcz"/><path class="hw-am7ogd"/><path class="iucsj8b6e"/><path class="n9vqu6frf"/><path class="kg7-urb4q"/><path class="b96xznzsu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:skateboarding-round-linear" /></template>
<style>
.b96xznzsu {
  stroke-linejoin: round;
  d: path("M17 21H17.0001");
}

.bahctlbqr {
  d: path("M3 17L3.60827 17.6759C4.36684 18.5187 5.4475 19 6.58145 19H17.4186C18.5525 19 19.6332 18.5187 20.3917 17.6759L21 17");
}

.hw-am7ogd {
  d: path("M15 16.5V14.3664C15 13.8174 14.7561 13.2967 14.3344 12.9453L13.3379 12.1149C12.6195 11.5162 12.5702 10.4298 13.2315 9.76847L14.8855 8.11449C15.4193 7.58066 15.2452 6.67647 14.5513 6.37908C13.2663 5.82836 11.793 5.94181 10.6075 6.68276L8.5 7.99996");
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.iucsj8b6e {
  d: path("M11 14L10.3787 14.6213C9.94513 15.0549 9.72836 15.2716 9.4527 15.3858C9.17705 15.5 8.87049 15.5 8.25736 15.5H7");
}

.kg7-urb4q {
  stroke-linejoin: round;
  d: path("M7 21H7.0001");
}

.n9vqu6frf {
  d: path("M16.5 10H19.5");
}

.pyd8uurcz {
  cx: 19px;
  cy: 4px;
  r: 2px;
}

</style>
