<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path clip-rule="evenodd" class="r5t8hmb9s"/><path class="wr7sfdcai"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:map-pin-search-sharp-fill" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.r5t8hmb9s {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M18.6189 13L12 13L12 21.618L10.5093 22.9514L4.2918 16C2.8159 14.3499 2 12.2138 2 10C2 5.0294 6.0294 1 11 1C15.9706 1 20 5.0294 20 10C20 10.7988 19.8909 11.5655 19.4644 13.2182ZM14 10C14 11.6569 12.6569 13 11 13C9.3431 13 8 11.6569 8 10C8 8.3431 9.3431 7 11 7C12.6569 7 14 8.3431 14 10Z");
  stroke: none;
}

.wr7sfdcai {
  d: path("M20 18.5C20 19.8807 18.8807 21 17.5 21C16.1193 21 15 19.8807 15 18.5C15 17.1193 16.1193 16 17.5 16C18.8807 16 20 17.1193 20 18.5ZM19.2678 20.2678L21.2929 22.2929");
}

</style>
