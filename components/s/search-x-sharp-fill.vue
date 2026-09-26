<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path clip-rule="evenodd" class="k4l2uabex"/><path class="p9760fzsb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:search-x-sharp-fill" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.k4l2uabex {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M18 10C18 14.4183 14.4183 18 10 18C5.5817 18 2 14.4183 2 10C2 5.5817 5.5817 2 10 2C14.4183 2 18 5.5817 18 10ZM11.4142 10L13.1213 11.7071L11.7071 13.1213L10 11.4142L8.2929 13.1213L6.8787 11.7071L8.5858 10L6.8787 8.2929L8.2929 6.8787L10 8.5858L11.7071 6.8787L13.1213 8.2929L11.4142 10Z");
  stroke: none;
}

.p9760fzsb {
  d: path("M14.2929 14.2929L21.2929 21.2929");
}

</style>
