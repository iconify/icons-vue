<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="p-9ojdbwb"/><path class="xrac7hbxf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:underwear-two-tone" /></template>
<style>
.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.p-9ojdbwb {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M12 4L21 4C22.1046 4 23 4.8954 23 6L23 9.2792C23 10.1399 22.4492 10.9044 21.6324 11.1766L18.3178 12.2815C17.3784 12.5946 16.654 13.3512 16.3819 14.3034L15.1687 18.5494C14.9235 19.408 14.1387 20 13.2457 20L10.7543 20C9.8613 20 9.0765 19.408 8.8312 18.5493L7.6181 14.3034C7.346 13.3512 6.6216 12.5946 5.6822 12.2815L2.3676 11.1766C1.5508 10.9044 1 10.1399 1 9.2792L1 6C1 4.8954 1.8954 4 3 4Z");
  stroke: none;
}

.xrac7hbxf {
  d: path("M3 5L21 5C21.5523 5 22 5.4477 22 6L22 9.2792C22 9.7096 21.7246 10.0918 21.3162 10.2279L18.0016 11.3328C16.749 11.7503 15.7831 12.7591 15.4204 14.0287L14.2072 18.2747C14.0846 18.704 13.6922 19 13.2457 19L10.7543 19C10.3078 19 9.9154 18.704 9.7928 18.2747L8.5796 14.0287C8.2169 12.7591 7.251 11.7503 5.9984 11.3328L2.6838 10.2279C2.2754 10.0918 2 9.7096 2 9.2792L2 6C2 5.4477 2.4477 5 3 5Z");
}

</style>
