<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="t7l4jhy0j"/><path class="p188pubrr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:podium-sharp-duotone" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.p188pubrr {
  d: path("M1 17.25H23");
}

.t7l4jhy0j {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M20 5.75C20.5523 5.75 21 6.19772 21 6.75V17.25C21 17.8023 20.5523 18.25 20 18.25H4C3.44772 18.25 3 17.8023 3 17.25V13.75C3 13.1977 3.44772 12.75 4 12.75H8V10.25C8 9.69772 8.44772 9.25 9 9.25H13V6.75C13 6.19772 13.4477 5.75 14 5.75H20Z");
  stroke: none;
}

</style>
