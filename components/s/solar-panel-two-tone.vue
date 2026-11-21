<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="m2-shqt8x"/><path class="evrmvgu1t"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:solar-panel-two-tone" /></template>
<style>
.evrmvgu1t {
  d: path("M5.1828 4.7007C5.6823 3.6611 6.7335 3 7.8868 3L16.1132 3C17.2665 3 18.3177 3.6611 18.8172 4.7007L21.7003 10.7007C22.6574 12.6923 21.2059 15 18.9963 15L5.0037 15C2.7941 15 1.3426 12.6923 2.2997 10.7007ZM10 3L8.0779 15M14 3L15.9221 15M3.1169 9L20.8831 9M12 15V21M8 21H16");
}

.m2-shqt8x {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M12 16L5.0037 16C3.5316 16 2.3073 15.226 1.6177 14.1296C0.9281 13.0332 0.7607 11.5945 1.3984 10.2676L4.2815 4.2676C4.9475 2.8815 6.3491 2 7.8868 2L16.1132 2C17.6509 2 19.0525 2.8815 19.7186 4.2676L22.6016 10.2676C23.2393 11.5945 23.0719 13.0332 22.3823 14.1296C21.6927 15.226 20.4684 16 18.9963 16Z");
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
