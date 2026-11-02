<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="qhothtbth"/><path class="l2v9q2k3r"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:play-pause-duotone-sharp" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.l2v9q2k3r {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("m3 6l10 6l-10 6Zm14 0v12m4-12v12");
}

.qhothtbth {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("m3 6l10 6l-10 6Z");
}

</style>
