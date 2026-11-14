<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="o2dm2xmlp"/><path class="f9xxppbcw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:megaphone-line-duotone" /></template>
<style>
.f9xxppbcw {
  d: path("M4.2319 10.2934C8.4041 9.25311 11.6071 6.80551 13.8407 3.36301C14.4234 2.39321 15.9027 2.53961 16.2172 3.80101L18.9268 14.6683C19.2412 15.9297 18.0038 16.7536 17.034 16.1709C13.4458 14.1798 9.4686 13.5224 5.2963 14.5627C3.7438 14.9498 2.9681 14.3187 2.6294 12.9603C2.2907 11.6019 2.6794 10.6805 4.2319 10.2934Z");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.o2dm2xmlp {
  d: path("M6.42578 9.58325L7.56678 14.1599C7.86608 17.0139 7.57311 19.5604 8.49401 20.7736C9.24521 21.72 11.0888 21.2603 11.4535 19.8296C11.7454 18.5201 11.1647 16.1914 10.8655 14.1646M19.5918 5.3999C21.4918 6.7999 22.0918 10.0999 20.7918 12.0999");
  opacity: var(--svg-opacity--0-5, 0.5);
}

</style>
