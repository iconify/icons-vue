<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="tkqn8bcbd"/><path class="ktaac2b9w"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:plug-duotone-sharp" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.ktaac2b9w {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M6 7h12v10H6Zm6 10v4M9 3v4m6-4v4");
}

.tkqn8bcbd {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M6 7h12v10H6Z");
}

</style>
