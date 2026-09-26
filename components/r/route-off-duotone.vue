<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="bu-qqbhlr"/><path class="ixuensbem"/><path class="ayo73pbzj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:route-off-duotone" /></template>
<style>
.ayo73pbzj {
  d: path("M2 2L22 22");
}

.bu-qqbhlr {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M9.873 17L14 17C14.7956 17 15.5587 16.6839 16.1213 16.1213C16.5118 15.7308 17.145 15.7308 17.5355 16.1213C17.926 16.5118 17.926 17.145 17.5355 17.5355C16.5979 18.4732 15.3261 19 14 19L9.873 19C9.3694 20.9503 7.4942 22.2219 5.496 21.9681C3.4978 21.7143 2 20.0143 2 18C2 15.9857 3.4978 14.2857 5.496 14.0319C7.4942 13.7781 9.3694 15.0497 9.873 17Z");
  stroke: none;
}

.ixuensbem {
  stroke-opacity: 0.4;
  d: path("M18 12.3431L18 3M15 6L18 3L21 6");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
