<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="musryfdwh"/><path class="gdhr5quqz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:wolf-duocolor" /></template>
<style>
.gdhr5quqz {
  d: path("m21 11l-2 2l2 2l-5 2l-1 2c-.613 1.226-1.387 2-2 2h-2c-.613 0-1.387-.774-2-2l-1-2l-5-2l2-2l-2-2l1-1c.64-.64 1-1.36 1-2V4c0-.369.631-.369 1 0l2 2c.64.64 1.36 1 2 1h4c.64 0 1.36-.36 2-1l2-2c.369-.369 1-.369 1 0v4c0 .64.36 1.36 1 2z");
}

.musryfdwh {
  stroke-opacity: 0.4;
  d: path("m9 11l1 1m5-1l-1 1m-2 6h.01");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
