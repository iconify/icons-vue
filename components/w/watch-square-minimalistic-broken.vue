<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="l3yrwhb1k"/><path class="vs49djbdr"/><path class="k8gt8ib7o"/><path class="emcs_sbus"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:watch-square-minimalistic-broken" /></template>
<style>
.emcs_sbus {
  d: path("M18.9614 9.2C18.8849 7.66459 18.6565 6.70674 17.9749 6.02513C16.9497 5 15.2998 5 12 5C8.70017 5 7.05025 5 6.02513 6.02513C5 7.05025 5 8.70017 5 12C5 15.2998 5 16.9497 6.02513 17.9749C7.05025 19 8.70017 19 12 19C15.2998 19 16.9497 19 17.9749 17.9749C18.7678 17.1819 18.9474 16.0151 18.9881 14");
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.k8gt8ib7o {
  d: path("M7 22H17");
}

.l3yrwhb1k {
  stroke-linejoin: round;
  d: path("M12 9V12.0769L14 14");
}

.vs49djbdr {
  d: path("M7 2H17");
}

</style>
