<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="r6ujkytqq"/><path class="zitfg43nb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:note-pin-corner-duocolor-round" /></template>
<style>
.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.r6ujkytqq {
  stroke-opacity: 0.4;
  d: path("M15 13h4v3l1 1c.369.369-.262 1-1 1h-4c-.738 0-1.369-.631-1-1l1-1zm-1 0h6m-3 5v3");
}

.zitfg43nb {
  d: path("M8 20a4 4 0 0 1-4-4V8a4 4 0 0 1 4-4h8a4 4 0 0 1 4 4");
}

</style>
