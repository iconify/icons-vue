<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="d34ut4blf"/><path class="e-ge8jqgg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:parasol-sharp-fill" /></template>
<style>
.d34ut4blf {
  fill: currentColor;
  d: path("M1 14C1 11.0443 3.0505 8.5351 5.1896 6.5218C7.6439 4.2119 9.6399 2.9459 11.2929 1.2929C11.6834 0.9024 12.3166 0.9024 12.7071 1.2929C14.3601 2.9459 16.3561 4.2119 18.8104 6.5218C20.9495 8.5351 23 11.0443 23 14C23 15.0047 21.6845 15.382 21.152 14.53C20.2937 13.1567 18.7063 13.1567 17.848 14.53C17.4563 15.1567 16.5437 15.1567 16.152 14.53C15.2937 13.1567 13.7063 13.1567 12.848 14.53C12.4563 15.1567 11.5437 15.1567 11.152 14.53C10.2937 13.1567 8.7063 13.1567 7.848 14.53C7.4563 15.1567 6.5437 15.1567 6.152 14.53C5.2937 13.1567 3.7063 13.1567 2.848 14.53C2.3155 15.382 1 15.0047 1 14Z");
  stroke: none;
}

.e-ge8jqgg {
  d: path("M12 14L12 23");
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
