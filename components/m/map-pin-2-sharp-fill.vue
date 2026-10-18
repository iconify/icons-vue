<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="kop6b_0_h"/><path class="ak69ehbee"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:map-pin-2-sharp-fill" /></template>
<style>
.ak69ehbee {
  d: path("M12 9L12 18M15.0085 15.1207L16 15.2505C19.6443 15.7276 22 16.8071 22 18C22 19.6569 17.5228 21 12 21C6.4772 21 2 19.6569 2 18C2 16.8071 4.3557 15.7276 8 15.2505L8.9915 15.1207");
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.kop6b_0_h {
  fill: currentColor;
  d: path("M16 6C16 8.2091 14.2091 10 12 10C9.7909 10 8 8.2091 8 6C8 3.7909 9.7909 2 12 2C14.2091 2 16 3.7909 16 6Z");
  stroke: none;
}

</style>
