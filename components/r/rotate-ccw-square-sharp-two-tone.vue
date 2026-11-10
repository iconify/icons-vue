<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="dz86qybwp"/><path class="k_ela376h"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:rotate-ccw-square-sharp-two-tone" /></template>
<style>
.dz86qybwp {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M15 10C15.552 10 16 10.45 16 11V22C16 22.55 15.552 23 15 23H4C3.448 23 3 22.55 3 22V11C3 10.45 3.448 10 4 10H15ZM15.372 2.46L14.528 3.25H20C20.552 3.25 21 3.7 21 4.25V10H19V5.25H14.529L15.4 6.07L14.032 7.53L11.316 4.98C11.115 4.79 11 4.53 11 4.25C11 3.97 11.115 3.71 11.316 3.52L14.005 1L15.372 2.46Z");
  stroke: none;
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.k_ela376h {
  d: path("M14.688 1.73L12 4.25L14.716 6.8M12 4.25H20V10M15 22V11H4V22H15Z");
}

</style>
