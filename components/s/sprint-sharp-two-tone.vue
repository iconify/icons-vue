<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="luh7sjb3b"/><path class="y6d9fygvo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:sprint-sharp-two-tone" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.luh7sjb3b {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M21.1213 2.8787C21.6631 3.4205 22 4.1718 22 5C22 6.6569 20.6569 8 19 8C17.3431 8 16 6.6569 16 5C16 3.3431 17.3431 2 19 2C19.8282 2 20.5795 2.3369 21.1213 2.8787Z");
  stroke: none;
}

.y6d9fygvo {
  d: path("M19.6838 12.2721L19 12.5L16 13.5001L15 9.5L9 8.5L6 11.5L5.7071 11.7929M2.5615 21.1725L6.5 18.4999L7 16L7.1608 15.1961M10.7 20.4L11 20L14 16L10 13.5L14.5 9.5L14.5615 9.4453M19 3C20.1046 3 21 3.8954 21 5C21 6.1046 20.1046 7 19 7C17.8954 7 17 6.1046 17 5C17 3.8954 17.8954 3 19 3Z");
}

</style>
