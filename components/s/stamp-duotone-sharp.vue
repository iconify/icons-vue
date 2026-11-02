<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="bb3dxgbic"/><path class="jp9-cujlx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:stamp-duotone-sharp" /></template>
<style>
.bb3dxgbic {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M9 11V8.38a3.828 3.828 0 0 1 5.601-5.189A3.83 3.83 0 0 1 15 8.38V11h5a1 1 0 0 1 1 1v5a1 1 0 0 1-1 1H4a1 1 0 0 1-1-1v-5a1 1 0 0 1 1-1Z");
}

.ft5dv1b6b {
  fill: none;
}

.jp9-cujlx {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M4 12h16v5H4Zm1 9h14m-9-9V8a2.828 2.828 0 1 1 4 0v4");
}

</style>
