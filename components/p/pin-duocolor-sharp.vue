<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="twahlgidx"/><path class="t7_v8gbpl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:pin-duocolor-sharp" /></template>
<style>
.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.t7_v8gbpl {
  d: path("M12 3h4a2 2 0 1 1 0 4a1 1 0 0 0-1 1v3c0 2 4 2 4 4v1a1 1 0 0 1-1 1H6a1 1 0 0 1-1-1v-1c0-2 4-2 4-4V8a1 1 0 0 0-1-1a2 2 0 1 1 0-4Z");
}

.twahlgidx {
  stroke-opacity: 0.4;
  d: path("M12 17v4");
}

</style>
