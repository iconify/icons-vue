<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="zjcm6o08i"/><path class="p9760fzsb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:search-slash-sharp-fill" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.p9760fzsb {
  d: path("M14.2929 14.2929L21.2929 21.2929");
}

.zjcm6o08i {
  fill: currentColor;
  d: path("M18 10C18 14.4183 14.4183 18 10 18C5.5817 18 2 14.4183 2 10C2 5.5817 5.5817 2 10 2C14.4183 2 18 5.5817 18 10ZM13.1213 8.2929L11.7071 6.8787L6.8787 11.7071L8.2929 13.1213L13.1213 8.2929Z");
  stroke: none;
}

</style>
