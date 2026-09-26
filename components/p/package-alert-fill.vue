<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path clip-rule="evenodd" class="j6ddfqney"/><path class="ejqcdexxx"/><path class="w8slmsefx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:package-alert-fill" /></template>
<style>
.ejqcdexxx {
  d: path("M2.3084 7.0066L12 12M12 12L21.6916 7.0066M7 4.3017L17 9.4239M12 12L12 22C11.6888 22 11.3776 21.9274 11.0925 21.7822L3.0925 17.7086C2.4221 17.3672 2 16.6786 2 15.9263L2 8.0737C2 7.3214 2.4221 6.6328 3.0925 6.2914L11.0925 2.2178C11.6627 1.9274 12.3373 1.9274 12.9075 2.2178L20.9075 6.2914C21.5779 6.6328 22 7.3214 22 8.0737L22 12M19 16V18");
}

.j6ddfqney {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M21.6916 7.0066C21.8894 7.3203 22 7.6886 22 8.0737L22 13L16 13C14.3431 13 13 14.3431 13 16L13 22L12 22C11.6888 22 11.3776 21.9274 11.0925 21.7822L3.0925 17.7086C2.4221 17.3672 2 16.6786 2 15.9263L2 8.0737C2 7.6886 2.1106 7.3203 2.3084 7.0066L12 12L21.6916 7.0066Z");
  stroke: none;
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.w8slmsefx {
  fill: currentColor;
  d: path("M20 22C20 22.5523 19.5523 23 19 23C18.4477 23 18 22.5523 18 22C18 21.4477 18.4477 21 19 21C19.5523 21 20 21.4477 20 22Z");
  stroke: none;
}

</style>
