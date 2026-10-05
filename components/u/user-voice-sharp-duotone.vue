<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="fs-evbclu"/><path class="s46epgcye"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:user-voice-sharp-duotone" /></template>
<style>
.fs-evbclu {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M8 13L10 13C13.7279 13 17 16.2721 17 20L17 21C17 21.5523 16.5523 22 16 22L2 22C1.4477 22 1 21.5523 1 21L1 20C1 16.2721 4.2721 13 8 13ZM9 3C11.0711 3 13 4.9289 13 7C13 9.0711 11.0711 11 9 11C6.9289 11 5 9.0711 5 7C5 4.9289 6.9289 3 9 3Z");
  stroke: none;
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.s46epgcye {
  d: path("M16.7867 2.4444L17.0623 3C17.6791 4.2432 18 5.6122 18 7C18 8.3878 17.6791 9.7568 17.0623 11L16.7867 11.5556M21.1454 2.3077L21.3693 3C21.7872 4.2922 22 5.6419 22 7C22 9.282 21.3993 11.5238 20.2583 13.5L19.9696 14");
}

</style>
