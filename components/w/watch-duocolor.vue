<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="mwg9_qb3b"/><path class="b1whqq4fp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:watch-duocolor" /></template>
<style>
.b1whqq4fp {
  d: path("M7 12a5 5 0 1 0 10 0a5 5 0 0 0-10 0m2-4V5a2 2 0 0 1 2-2h2a2 2 0 0 1 2 2v3m-6 8v3a2 2 0 0 0 2 2h2a2 2 0 0 0 2-2v-3");
}

.mwg9_qb3b {
  stroke-opacity: 0.4;
  d: path("M12 10v2h2");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
