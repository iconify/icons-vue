<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="i2_k1ib1h"/><path class="k1rh1gkoh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:music-note-off-sharp-fill" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.i2_k1ib1h {
  fill: currentColor;
  d: path("M10 18C10 20.0711 8.0711 22 6 22C3.9289 22 2 20.0711 2 18C2 15.9289 3.9289 14 6 14C8.0711 14 10 15.9289 10 18ZM14.3535 14.3535L19.6465 19.6465C19.1443 19.8736 18.5869 20 18 20C15.7909 20 14 18.2091 14 16C14 15.4131 14.1264 14.8557 14.3535 14.3535Z");
  stroke: none;
}

.k1rh1gkoh {
  d: path("M9 18L9 9M9.4338 4.9277L21 3L21 16.3431M1.7071 1.7071L22.2929 22.2929");
}

</style>
