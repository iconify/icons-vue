<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="h1bfdub8k"/><path class="q45o5bc9i"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:plug-zap-fill" /></template>
<style>
.h1bfdub8k {
  d: path("M7.6569 13.5147L10.0139 11.1577M10.4853 16.3431L12.8423 13.9861M3.8856 20.1144L2 22M20.5 2L16 6.5L22 6.5L17.5 11");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.q45o5bc9i {
  fill: currentColor;
  d: path("M7.8925 12.3362L11.6638 16.1075C12.8354 17.279 12.8354 19.1785 11.6638 20.3501L11.1924 20.8215C8.9794 23.0345 5.3915 23.0344 3.1785 20.8215C0.9656 18.6085 0.9655 15.0206 3.1785 12.8076L3.6499 12.3362C4.8215 11.1646 6.721 11.1646 7.8925 12.3362Z");
  stroke: none;
}

</style>
