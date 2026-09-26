<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="snfm_wb7w"/><path class="ei_je2b_p"/><path class="tni6f7iwc"/><path class="ju8v6k8zc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:triangle-alert-two-tone" /></template>
<style>
.ei_je2b_p {
  d: path("M14.4051 4.39215C13.3181 2.53595 10.6819 2.53595 9.5949 4.39215L2.40063 16.6777C1.28536 18.5822 2.63072 21 4.80572 21H19.1943C21.3693 21 22.7146 18.5822 21.5994 16.6777L14.4051 4.39215Z");
}

.ju8v6k8zc {
  fill: currentColor;
  d: path("M13 17C13 17.5523 12.5523 18 12 18C11.4477 18 11 17.5523 11 17C11 16.4477 11.4477 16 12 16C12.5523 16 13 16.4477 13 17Z");
  stroke: none;
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.snfm_wb7w {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M8.73282 3.88688C10.2061 1.37155 13.7947 1.37151 15.268 3.88688L22.4623 16.172C23.9502 18.7134 22.1759 21.9998 19.1947 22.0002H4.80607C1.82451 22.0001 0.0501869 18.7136 1.53849 16.172L8.73282 3.88688Z");
  stroke: none;
}

.tni6f7iwc {
  d: path("M12 9V13");
}

</style>
