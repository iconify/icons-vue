<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="l46nqoumc"/><path class="mb0exzb9v"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:slider-sharp-two-tone" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.l46nqoumc {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M17 14C18.864 14 20.43 15.27 20.874 17H23V19H20.874C20.43 20.73 18.864 22 17 22H15C13.136 22 11.57 20.73 11.126 19H1V17H11.126C11.57 15.27 13.136 14 15 14H17ZM10 2C10.552 2 11 2.45 11 3V11C11 11.55 10.552 12 10 12H2C1.448 12 1 11.55 1 11V3C1 2.45 1.448 2 2 2H10ZM18 2C20.761 2 23 4.24 23 7C23 9.76 20.761 12 18 12C15.239 12 13 9.76 13 7C13 4.24 15.239 2 18 2Z");
  stroke: none;
}

.mb0exzb9v {
  d: path("M20 18C20 16.34 18.657 15 17 15H15C13.343 15 12 16.34 12 18M20 18C20 19.66 18.657 21 17 21H15C13.343 21 12 19.66 12 18M20 18H23M12 18H1M2 3V11H10V3H2ZM22 7C22 4.79 20.209 3 18 3C15.791 3 14 4.79 14 7C14 9.21 15.791 11 18 11C20.209 11 22 9.21 22 7Z");
}

</style>
