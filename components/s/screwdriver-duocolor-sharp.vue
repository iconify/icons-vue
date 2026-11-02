<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="b3e1orbda"/><path class="fd8zyjxyy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:screwdriver-duocolor-sharp" /></template>
<style>
.b3e1orbda {
  stroke-opacity: 0.4;
  d: path("m13 11l7-7");
}

.fd8zyjxyy {
  d: path("m4 16l7-7l4 4l-7 7a2.828 2.828 0 1 1-4-4");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
