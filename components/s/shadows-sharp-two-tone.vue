<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="s7-03ub-n"/><path class="w-u-gkbeu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:shadows-sharp-two-tone" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.s7-03ub-n {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M12 1C15.599 1 18.795 2.73 20.8 5.3994L20.978 5.6416C21.846 6.8654 22.471 8.2756 22.78 9.8008C22.925 10.512 23 11.2479 23 12C23 12.7521 22.925 13.488 22.78 14.1992C22.45 15.826 21.76 17.3219 20.8 18.6006C18.795 21.27 15.599 23 12 23C5.925 23 1 18.0751 1 12C1 5.9249 5.925 1 12 1Z");
  stroke: none;
}

.w-u-gkbeu {
  d: path("M12 2C6.477 2 2 6.4772 2 12C2 17.5228 6.477 22 12 22M12 2C15.272 2 18.176 3.5711 20.001 6M12 2V22M12 22C15.272 22 18.176 20.4289 20.001 18M20.001 6C20.874 7.1628 21.5 8.5222 21.8 10C21.931 10.6462 22 11.3151 22 12C22 12.6849 21.931 13.3538 21.8 14C21.5 15.4777 20.874 16.8372 20.001 18M20.001 18H12M21.8 14H12M21.8 10H12M20.001 6H12");
}

</style>
