<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="sh0wczrsv"/><path class="nry2q-bud"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:table-rows-merge-previous-sharp-two-tone" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.nry2q-bud {
  d: path("M3 21L21 21L21 3L3 3L3 21ZM3 17L21 17M3 8L6 8M21 8L18 8M12 14L12 7M8.7071 10.2929L12 7L15.2929 10.2929");
}

.sh0wczrsv {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M3 22L21 22C21.5523 22 22 21.5523 22 21L22 3C22 2.4477 21.5523 2 21 2L3 2C2.4477 2 2 2.4477 2 3L2 21C2 21.5523 2.4477 22 3 22ZM3 17L21 17L21 21L3 21L3 17Z");
  stroke: none;
}

</style>
