<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="ld8hjv5zq"/><path class="yxkxzw26j"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:mailbox-duocolor-sharp" /></template>
<style>
.ld8hjv5zq {
  stroke-opacity: 0.4;
  d: path("M17 9V3h4");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.yxkxzw26j {
  d: path("M7 9h14v12H3v-8a4 4 0 0 1 4-4m0 0a4 4 0 0 1 4 4v8");
}

</style>
