<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="s19aowben"/><path class="mvkasiemb"/><path class="zc6gsob1e"/><path class="j2m13bcqy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:playlist-minimalistic-line-duotone" /></template>
<style>
.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.j2m13bcqy {
  d: path("M14.25 13.5C14.25 11.604 14.25 10.656 14.6633 10.1174C14.9862 9.69661 15.4631 9.4213 15.9889 9.35206C16.662 9.26345 17.483 9.73744 19.125 10.6854C20.767 11.6334 21.588 12.1074 21.8478 12.7347C22.0507 13.2247 22.0507 13.7753 21.8478 14.2654C21.588 14.8926 20.767 15.3666 19.125 16.3146C17.483 17.2626 16.662 17.7366 15.9889 17.648C15.4631 17.5787 14.9862 17.3034 14.6633 16.8826C14.25 16.344 14.25 15.396 14.25 13.5Z");
}

.mvkasiemb {
  d: path("M10 16H3");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.s19aowben {
  d: path("M20 6L3 6");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.zc6gsob1e {
  d: path("M10 11H3");
  opacity: var(--svg-opacity--0-5, 0.5);
}

</style>
