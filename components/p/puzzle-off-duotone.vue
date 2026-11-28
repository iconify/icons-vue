<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="bm5c63n0q"/><path class="ayo73pbzj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:puzzle-off-duotone" /></template>
<style>
.ayo73pbzj {
  d: path("M2 2L22 22");
}

.bm5c63n0q {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M18 18.12V19C18 20.6569 16.657 22 15 22H5C3.343 22 2 20.6569 2 19V17.5C2 16.6716 2.672 16 3.5 16H4C5.105 16 6 15.1046 6 14C6 12.8954 5.105 12 4 12H3.5C2.672 12 2 11.3284 2 10.5V9C2 7.3431 3.343 6 5 6H5.88L18 18.12ZM20.075 15.8323L8.168 3.9252C7.987 3.7442 7.875 3.4942 7.875 3.2181C7.875 2.8023 8.129 2.4458 8.49 2.2949C8.956 2.1048 9.466 2 10 2C12.209 2 14 3.7908 14 6H15C16.657 6 18 7.3431 18 9V10C20.209 10 22 11.7908 22 14C22 14.5344 21.895 15.0442 21.705 15.5102C21.554 15.8714 21.198 16.1251 20.782 16.1251C20.506 16.1251 20.256 16.0133 20.075 15.8323Z");
  stroke: none;
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
