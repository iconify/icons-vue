<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="fayhp9evc"/><path clip-rule="evenodd" class="zfsdfebcz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:pizza-sharp" /></template>
<style>
.fayhp9evc {
  d: path("M2 22L5.296 2C13.8435 3.4612 20.5388 10.1565 22 18.704ZM4.6456 5.9469C11.5014 7.1291 16.8709 12.4986 18.0531 19.3544");
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.zfsdfebcz {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M8.8317 16.6683C8.8317 17.4967 8.1601 18.1683 7.3317 18.1683C6.5033 18.1683 5.8317 17.4967 5.8317 16.6683C5.8317 15.8399 6.5033 15.1683 7.3317 15.1683C8.1601 15.1683 8.8317 15.8399 8.8317 16.6683ZM9.6095 11.86C9.6095 12.6884 8.938 13.36 8.1095 13.36C7.2811 13.36 6.6095 12.6884 6.6095 11.86C6.6095 11.0315 7.2811 10.36 8.1095 10.36C8.938 10.36 9.6095 11.0315 9.6095 11.86ZM13.64 15.8905C13.64 16.7189 12.9685 17.3905 12.14 17.3905C11.3116 17.3905 10.64 16.7189 10.64 15.8905C10.64 15.062 11.3116 14.3905 12.14 14.3905C12.9685 14.3905 13.64 15.062 13.64 15.8905Z");
  stroke: none;
}

</style>
