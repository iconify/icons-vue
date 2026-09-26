<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="ksspywt0b"/><path class="lsal2z6ms"/><path class="r07r6nw5l"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:wind-turbine-duotone" /></template>
<style>
.ksspywt0b {
  stroke-opacity: 0.4;
  d: path("M12 13L12 22M5 22L19 22M16 2.5718C18.4752 4.0009 20 6.6419 20 9.5C20 9.5146 20 9.5292 19.9999 9.5438M4.0001 9.5438C4 9.5292 4 9.5146 4 9.5C4 6.6419 5.5248 4.0009 8 2.5718");
}

.lsal2z6ms {
  fill: currentColor;
  d: path("M15.5 9.5C15.5 11.433 13.933 13 12 13C10.067 13 8.5 11.433 8.5 9.5C8.5 7.567 10.067 6 12 6C13.933 6 15.5 7.567 15.5 9.5Z");
  stroke: none;
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.r07r6nw5l {
  d: path("M12 6L12 2M15.0311 11.25L18.4952 13.25M8.9689 11.25L5.5048 13.25");
}

</style>
