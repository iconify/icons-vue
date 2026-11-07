<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="kqohs1bhy"/><path class="j-x5i4bhp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:moon-duotone-sharp" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.j-x5i4bhp {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M21 12a9 9 0 1 1-9-9a6.403 6.403 0 1 0 9 9");
}

.kqohs1bhy {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M12 3a6.403 6.403 0 1 0 9 9a9 9 0 0 1-9 9a9 9 0 0 1-9-9a9 9 0 0 1 9-9");
}

</style>
