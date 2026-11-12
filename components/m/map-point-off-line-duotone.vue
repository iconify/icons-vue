<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="rsrhfac5n"/><path class="n-34dfvcb"/><path class="kt2wmfb9s"/><path class="u3c5cbc9o"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:map-point-off-line-duotone" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.kt2wmfb9s {
  d: path("M19.6624 7.79358C19.8822 8.53758 20.0004 9.32638 20.0004 10.1433C20.0004 14.6055 17.4471 19.8124 13.4633 21.6744C12.5347 22.1085 11.4661 22.1085 10.5375 21.6744C9.52226 21.1999 8.59986 20.5082 7.78906 19.6669");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.n-34dfvcb {
  d: path("M6.2718 17.7282C4.8262 15.4607 4 12.6815 4 10.1433C4 5.6459 7.5817 2 12 2C14.7043 2 17.0952 3.3658 18.5432 5.4568");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.rsrhfac5n {
  d: path("M22 2L2 22");
}

.u3c5cbc9o {
  d: path("M11.1285 12.8715C9.8967 12.4981 9 11.3538 9 10C9 8.3431 10.3431 7 12 7C13.3538 7 14.4981 7.8967 14.8715 9.1285");
}

</style>
