<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="h5kldm4gm"/><path class="x6ct0lbbk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:play-duotone" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.h5kldm4gm {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M19.029 10.285a2 2 0 0 1 0 3.43l-10 6A1.999 1.999 0 0 1 6 18V6a2 2 0 0 1 3.029-1.715Z");
}

.x6ct0lbbk {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("m9.029 4.285l10 6c1.295.777 1.295 2.653 0 3.43l-10 6C7.696 20.515 6 19.555 6 18V6c0-1.555 1.696-2.515 3.029-1.715");
}

</style>
