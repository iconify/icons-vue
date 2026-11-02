<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="ngtiubbgl"/><path class="myadcub7g"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:note-edit-duocolor-sharp" /></template>
<style>
.myadcub7g {
  d: path("M11 4H4v16h16v-7");
}

.ngtiubbgl {
  stroke-opacity: 0.4;
  d: path("M9 15v-3l9-9l3 3l-9 9Zm6-9l3 3");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
