<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="hhlrbab5g"/><path class="s4x2idbng"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:phone-off-sharp-two-tone" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.hhlrbab5g {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M10.8076 13.1924C11.8136 14.1984 12.9779 15.0324 14.2541 15.6612L15.2 14.4C15.3889 14.1482 15.6852 14 16 14L22 14C22.5523 14 23 14.4477 23 15L23 22C23 22.5523 22.5523 23 22 23L20 23C14.9609 23 10.1282 20.9982 6.565 17.435ZM4.6122 15.1452C2.2642 11.9034 1 8.0028 1 4L1 2C1 1.4477 1.4477 1 2 1L9 1C9.5523 1 10 1.4477 10 2L10 8C10 8.3148 9.8518 8.6111 9.6 8.8L8.3388 9.7459C8.5202 10.1141 8.719 10.4735 8.9344 10.823Z");
  stroke: none;
}

.s4x2idbng {
  d: path("M10.1005 13.8995C11.3822 15.1812 12.9007 16.2018 14.5715 16.9047L16 15L22 15L22 22L20 22C15.2261 22 10.6477 20.1036 7.2721 16.7279M22.2929 1.7071L1.7071 22.2929");
}

</style>
