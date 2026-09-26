<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="qf8p8ebcz"/><path class="mm_ae4bze"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:user-voice-sharp-two-tone" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.mm_ae4bze {
  d: path("M9 14L11 14C14.3137 14 17 16.6863 17 20L17 21L3 21L3 20C3 16.6863 5.6863 14 9 14ZM10 4C11.6569 4 13 5.3431 13 7C13 8.6569 11.6569 10 10 10C8.3431 10 7 8.6569 7 7C7 5.3431 8.3431 4 10 4ZM15.5622 2.634L16.0622 3.5C16.6766 4.5641 17 5.7712 17 7C17 8.2288 16.6766 9.4359 16.0622 10.5L15.5622 11.366M19.9985 2.3636L20.247 3C20.7446 4.2749 21 5.6314 21 7C21 8.9309 20.4917 10.8278 19.5263 12.5L19.0263 13.366");
}

.qf8p8ebcz {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M9 13L11 13C14.7279 13 18 16.2721 18 20L18 21C18 21.5523 17.5523 22 17 22L3 22C2.4477 22 2 21.5523 2 21L2 20C2 16.2721 5.2721 13 9 13ZM10 3C12.0711 3 14 4.9289 14 7C14 9.0711 12.0711 11 10 11C7.9289 11 6 9.0711 6 7C6 4.9289 7.9289 3 10 3Z");
  stroke: none;
}

</style>
