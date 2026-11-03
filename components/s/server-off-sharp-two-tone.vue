<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path clip-rule="evenodd" class="fitpcjboc"/><path clip-rule="evenodd" class="ne0ewsb8r"/><path class="dkw-d8_9n"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:server-off-sharp-two-tone" /></template>
<style>
.dkw-d8_9n {
  d: path("M10 10L4 10L4 4M20 20L20 22L4 22L4 14L14 14M1.7071 1.7071L22.2929 22.2929");
}

.fitpcjboc {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  fill-rule: evenodd;
  d: path("M11 11L4 11C3.4477 11 3 10.5523 3 10L3 3L11 11ZM21 21L21 22C21 22.5523 20.5523 23 20 23L4 23C3.4477 23 3 22.5523 3 22L3 14C3 13.4477 3.4477 13 4 13L13 13L21 21ZM4.7426 1L20 1C20.5523 1 21 1.4477 21 2L21 10C21 10.5523 20.5523 11 20 11L14.7426 11L4.7426 1ZM16.7426 13L20 13C20.5523 13 21 13.4477 21 14L21 17.2574L16.7426 13Z");
  stroke: none;
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.ne0ewsb8r {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M13 6C13 6.5523 12.5523 7 12 7C11.4477 7 11 6.5523 11 6C11 5.4477 11.4477 5 12 5C12.5523 5 13 5.4477 13 6ZM9 18C9 18.5523 8.5523 19 8 19C7.4477 19 7 18.5523 7 18C7 17.4477 7.4477 17 8 17C8.5523 17 9 17.4477 9 18ZM13 18C13 18.5523 12.5523 19 12 19C11.4477 19 11 18.5523 11 18C11 17.4477 11.4477 17 12 17C12.5523 17 13 17.4477 13 18Z");
  stroke: none;
}

</style>
