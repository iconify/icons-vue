<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="tl7pvfbbg"/><path class="a14vpk97p"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:wind-turbine-duotone-sharp" /></template>
<style>
.a14vpk97p {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M10 10a2 2 0 1 0 4 0a2 2 0 0 0-4 0m2 2v9m-4 0h8M12 8V3c1.5 1 2 3 1.41 5.59Zm1.732 3l4.33 2.5c-1.616.799-3.598.232-5.546-1.574Zm-3.464 0l-4.33 2.5c.116-1.799 1.598-3.232 4.136-4.016Z");
}

.ft5dv1b6b {
  fill: none;
}

.tl7pvfbbg {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M12 8V3c1.835 1.226 1.85 3.657 1.41 5.59Zm-1.732 3l-4.33 2.5c.144-2.202 2.242-3.43 4.136-4.016Zm3.464 0l4.33 2.5c-1.979.977-4.092-.227-5.546-1.574Z");
}

</style>
