<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="g9vxpxqky"/><path class="elg-n3b8i"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:megaphone-duocolor" /></template>
<style>
.elg-n3b8i {
  d: path("m11 8l8-4c.919-.46 2 .081 2 1v12c0 .919-1.081 1.46-2 1l-8-4zm0 0H5a2 2 0 0 0-2 2v2a2 2 0 0 0 2 2h6");
}

.g9vxpxqky {
  stroke-opacity: 0.4;
  d: path("M5 14v5a2 2 0 1 0 4 0v-5");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
