<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="ftbyj6eil"/><path class="d3fqwacwl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:package-minus-duotone-round" /></template>
<style>
.d3fqwacwl {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M5 6c.613-1.226 1.774-2 3-2h8c1.226 0 2.387.774 3 2l1 2v8a4 4 0 0 1-4 4H8a4 4 0 0 1-4-4V8zM4 8h16M9 14h6");
}

.ft5dv1b6b {
  fill: none;
}

.ftbyj6eil {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M5 6c.569-1.137 1.695-1.999 3-2h8c1.305.001 2.431.863 3 2l1 2H4Z");
}

</style>
