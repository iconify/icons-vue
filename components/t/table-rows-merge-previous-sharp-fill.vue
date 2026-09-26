<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="xn0asdbab"/><path class="nry2q-bud"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:table-rows-merge-previous-sharp-fill" /></template>
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

.xn0asdbab {
  fill: currentColor;
  d: path("M3 17L3 21L21 21L21 17L3 17Z");
  stroke: none;
}

</style>
