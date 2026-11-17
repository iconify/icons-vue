<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="ygu7sub4z"/><path class="oq-16lb7f"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:synagogue-duotone" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.oq-16lb7f {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 21H6a2 2 0 0 1-2-2V9c0-.613.774-1.387 2-2l6-3l6 3c1.226.613 2 1.387 2 2v10a2 2 0 0 1-2 2zm0-12l3.464 6H8.536Zm0 8l3.464-6H8.536Z");
}

.ygu7sub4z {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M6 21a2 2 0 0 1-2-2V9c.001-.85 1.349-1.674 2-2l6-3l6 3c.651.326 1.999 1.15 2 2v10a2 2 0 0 1-2 2Z");
}

</style>
