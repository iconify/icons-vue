<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="tkcfsdpwo"/><path class="p7_mvdqwe"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:triangles-centerline-inward-horizontal-sharp-two-tone" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.p7_mvdqwe {
  d: path("M23 12H1M12 8.26L7.777 2H16.223L12 8.26ZM12 15.74L7.777 22H16.223L12 15.74Z");
}

.tkcfsdpwo {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M12 14.74C12.332 14.74 12.643 14.91 12.829 15.18L17.053 21.44C17.259 21.75 17.28 22.14 17.106 22.47C16.933 22.8 16.593 23 16.224 23H7.777C7.408 23 7.068 22.8 6.895 22.47C6.721 22.14 6.741 21.75 6.948 21.44L11.206 15.13C11.395 14.92 11.709 14.74 12 14.74ZM23 13H1V11H23V13ZM16.223 1C16.592 1 16.932 1.2 17.105 1.53C17.279 1.86 17.259 2.25 17.052 2.56L12.828 8.82C12.642 9.09 12.331 9.26 11.999 9.26C11.667 9.26 11.357 9.09 11.171 8.82L6.947 2.56C6.741 2.25 6.72 1.86 6.894 1.53C7.067 1.2 7.407 1 7.776 1H16.223Z");
  stroke: none;
}

</style>
