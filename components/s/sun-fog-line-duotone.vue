<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="lt7j86jjt"/><path class="cjpkl_0zw"/><path class="l6md27rub"/><path class="tnrcavb0v"/><path class="je0pbq8pu"/><path class="xnx0ex6ho"/><path class="n8-rodbwi"/><path class="n_ucwybmv"/><path class="uq9j8rbvn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:sun-fog-line-duotone" /></template>
<style>
.cjpkl_0zw {
  stroke-linejoin: round;
  d: path("M5 19H19");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.je0pbq8pu {
  d: path("M12 2V3");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.l6md27rub {
  stroke-linejoin: round;
  d: path("M2 16H22");
}

.lt7j86jjt {
  stroke-linejoin: round;
  d: path("M8 22H16");
}

.n_ucwybmv {
  d: path("M19.0703 4.9292L18.6775 5.32204");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.n8-rodbwi {
  d: path("M3 12L2 12");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.tnrcavb0v {
  d: path("M6 12C6 8.68629 8.68629 6 12 6C15.3137 6 18 8.68629 18 12C18 13.5217 17.4335 14.911 16.5 15.9687H7.5C6.56645 14.911 6 13.5217 6 12Z");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.uq9j8rbvn {
  d: path("M5.32227 5.32178L4.92943 4.92894");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.xnx0ex6ho {
  d: path("M22 12L21 12");
  opacity: var(--svg-opacity--0-5, 0.5);
}

</style>
