<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="jus-9cble"/><path class="r0fzdm12c"/><path class="l18eabbfs"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:volume-off-sharp-two-tone" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.jus-9cble {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M12 12V20.0009C12 20.8863 10.9341 21.3349 10.301 20.7159L5.4777 16H2C1.4477 16 1 15.5523 1 15V9C1 8.4477 1.4477 8 2 8H5.4777L6.5128 6.5128L12 12Z");
  stroke: none;
}

.l18eabbfs {
  d: path("M11 11V22L6.0001 15H2V9H6.0001L7.2312 7.2312M1.7071 1.7071L22.2929 22.2929");
}

.r0fzdm12c {
  stroke-opacity: 0.4;
  d: path("M15.4907 6.6131L15.8044 6.9091C17.2058 8.2316 18 10.0732 18 12C18 12.112 18 12.2238 17.992 12.3351L17.9444 13.334M18.2362 3.704L18.5498 4C20.7519 6.0782 22 8.9721 22 12C22 13.2746 21.7788 14.5254 21.3585 15.7016L21.022 16.6433");
}

</style>
