<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="omf3owutt"/><path class="e6rdkwtod"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:smartphone-nfc-sharp-duotone" /></template>
<style>
.e6rdkwtod {
  d: path("M5 8L6 8L8 8L9 8M17.1101 7.552L17.4283 8.5C17.8069 9.6281 18 10.8101 18 12C18 13.1899 17.8069 14.3719 17.4283 15.5L17.1101 16.448M21.0091 6.5461L21.3091 7.5C21.767 8.9561 22 10.4736 22 12C22 13.5264 21.767 15.0439 21.3091 16.5L21.0091 17.4539");
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.omf3owutt {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M12 3C12.5523 3 13 3.44772 13 4V20C13 20.5523 12.5523 21 12 21H2C1.44772 21 1 20.5523 1 20V4C1 3.44772 1.44772 3 2 3H12Z");
  stroke: none;
}

</style>
