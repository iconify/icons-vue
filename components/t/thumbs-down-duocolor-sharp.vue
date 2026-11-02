<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="ttgt51b0w"/><path class="yr7yzpbys"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:thumbs-down-duocolor-sharp" /></template>
<style>
.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.ttgt51b0w {
  stroke-opacity: 0.4;
  d: path("M7 14H3V3h4z");
}

.yr7yzpbys {
  d: path("M7 14a4 4 0 0 1 4 4v1a2 2 0 1 0 4 0v-5h6v-4l-2-7H7");
}

</style>
