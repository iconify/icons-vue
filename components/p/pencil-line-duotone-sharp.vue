<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="s-q6s911c"/><path class="dn67hmb4z"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:pencil-line-duotone-sharp" /></template>
<style>
.dn67hmb4z {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M4 20v-4L16 4l4 4L8 20zm8-12l4 4m-8 8h12");
}

.ft5dv1b6b {
  fill: none;
}

.s-q6s911c {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M3 16c0-.265.105-.52.293-.707l12-12a1 1 0 0 1 1.414 0l4 4a1 1 0 0 1 0 1.414l-12 12A1 1 0 0 1 8 21H4a1 1 0 0 1-1-1Z");
}

</style>
