<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="ky8hevb5b"/><path class="ahhqo1b4s"/><path class="ambqkebxn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:power-off-sharp-duotone" /></template>
<style>
.ahhqo1b4s {
  d: path("M1.7071 1.7071L22.2929 22.2929");
}

.ambqkebxn {
  stroke-opacity: 0.4;
  d: path("M18.0886 4.0045L18.82 4.6865C20.8483 6.5779 22 9.2267 22 12C22 13.2499 21.7657 14.4887 21.3092 15.6523L20.944 16.5832M12 1L12 7.3431");
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.ky8hevb5b {
  stroke-opacity: 0.4;
  d: path("M19.0711 19.0711C17.1957 20.9464 14.6522 22 12 22C6.4772 22 2 17.5228 2 12C2 9.3478 3.0536 6.8043 4.9289 4.9289");
}

</style>
