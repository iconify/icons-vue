<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="gv2jrdtmw"/><path class="nua731fgb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:sun-medium-two-tone" /></template>
<style>
.gv2jrdtmw {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M17.5 12C17.5 15.0376 15.0376 17.5 12 17.5C8.9624 17.5 6.5 15.0376 6.5 12C6.5 8.9624 8.9624 6.5 12 6.5C15.0376 6.5 17.5 8.9624 17.5 12Z");
  stroke: none;
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.nua731fgb {
  d: path("M16.5 12C16.5 14.4853 14.4853 16.5 12 16.5C9.5147 16.5 7.5 14.4853 7.5 12C7.5 9.5147 9.5147 7.5 12 7.5C14.4853 7.5 16.5 9.5147 16.5 12ZM20.5 12L21 12M18.0104 18.0104L18.364 18.364M12 20.5L12 21M5.9896 18.0104L5.636 18.364M3.5 12L3 12M5.9896 5.9896L5.636 5.636M12 3.5L12 3M18.0104 5.9896L18.364 5.636");
}

</style>
