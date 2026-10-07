<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="pkxkeccnw"/><path class="wucegvl2w"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:notebook-pen-duotone" /></template>
<style>
.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.pkxkeccnw {
  stroke-opacity: 0.4;
  d: path("M20 12.1317L20 19C20 20.6569 18.6569 22 17 22L7 22C5.3431 22 4 20.6569 4 19L4 5C4 3.3431 5.3431 2 7 2L13.8683 2M2 7L6 7M2 12L6 12M2 17L6 17");
}

.wucegvl2w {
  fill: currentColor;
  d: path("M11.8714 13.4285L15.9962 11.7786C16.1219 11.7283 16.2361 11.653 16.3319 11.5572L22.1945 5.6945C23.2685 4.6206 23.2685 2.8794 22.1945 1.8055C21.1206 0.7315 19.3794 0.7315 18.3055 1.8055L12.4428 7.6681C12.347 7.7639 12.2717 7.8781 12.2214 8.0038L10.5715 12.1286C10.423 12.5 10.51 12.9242 10.7929 13.2071C11.0758 13.49 11.5 13.577 11.8714 13.4285Z");
  stroke: none;
}

</style>
