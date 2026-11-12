<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="lqr12dkxf"/><path class="u0ognac_v"/><path class="g46-gz07d"/><path class="d_y_0lfcd"/><path class="npwtzkbyw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:playlist-minimalistic-3-line-duotone" /></template>
<style>
.d_y_0lfcd {
  d: path("M16 17.4286C16 18.8487 14.8807 20 13.5 20C12.1193 20 11 18.8487 11 17.4286C11 16.0084 12.1193 14.8571 13.5 14.8571C14.8807 14.8571 16 16.0084 16 17.4286ZM16 17.4286V11");
}

.g46-gz07d {
  d: path("M12 9L3 9");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.lqr12dkxf {
  d: path("M20 4L3 4");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.npwtzkbyw {
  d: path("M16.9205 8.95812L18.675 8.11595C19.4652 7.73668 19.8603 7.54705 20.1799 7.60553C20.4327 7.65176 20.6579 7.79348 20.8089 8.00132C21 8.26422 21 8.70244 21 9.57889C21 9.95791 21 10.1474 20.9395 10.3134C20.8909 10.4466 20.8145 10.568 20.7155 10.6694C20.592 10.7958 20.4212 10.8778 20.0795 11.0418L18.325 11.884C17.5348 12.2633 17.1397 12.4529 16.8201 12.3944C16.5673 12.3482 16.3421 12.2065 16.1911 11.9986C16 11.7357 16 11.2975 16 10.4211C16 10.042 16 9.85252 16.0605 9.68654C16.1091 9.55334 16.1855 9.43199 16.2845 9.33055C16.408 9.20414 16.5788 9.12213 16.9205 8.95812Z");
}

.u0ognac_v {
  d: path("M8 14H3");
  opacity: var(--svg-opacity--0-5, 0.5);
}

</style>
