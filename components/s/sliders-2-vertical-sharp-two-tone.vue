<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="puy7etbrg"/><path class="man0khbue"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:sliders-2-vertical-sharp-two-tone" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.man0khbue {
  d: path("M4.5 6L9.5 6C9.7761 6 10 6.2239 10 6.5L10 13.5C10 13.7761 9.7761 14 9.5 14L4.5 14C4.2239 14 4 13.7761 4 13.5L4 6.5C4 6.2239 4.2239 6 4.5 6ZM14.5 10L19.5 10C19.7761 10 20 10.2239 20 10.5L20 17.5C20 17.7761 19.7761 18 19.5 18L14.5 18C14.2239 18 14 17.7761 14 17.5L14 10.5C14 10.2239 14.2239 10 14.5 10ZM7 2L7 6M7 14L7 22M17 2L17 10M17 18L17 22");
}

.puy7etbrg {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M4.5 5L9.5 5C10.3284 5 11 5.6716 11 6.5L11 13.5C11 14.3284 10.3284 15 9.5 15L4.5 15C3.6716 15 3 14.3284 3 13.5L3 6.5C3 5.6716 3.6716 5 4.5 5ZM14.5 9L19.5 9C20.3284 9 21 9.6716 21 10.5L21 17.5C21 18.3284 20.3284 19 19.5 19L14.5 19C13.6716 19 13 18.3284 13 17.5L13 10.5C13 9.6716 13.6716 9 14.5 9Z");
  stroke: none;
}

</style>
