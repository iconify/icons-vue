<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="lla1cob_j"/><path class="qdb5lgfip"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:martini-duotone-round" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.lla1cob_j {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M17 5a1.002 1.002 0 0 1 .707 1.707l-5 5a1 1 0 0 1-1.414 0l-5-5A1 1 0 0 1 7 5Z");
}

.qdb5lgfip {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 11L5 4c-.369-.369.262-1 1-1h12c.738 0 1.369.631 1 1zm0 0v10m-4 0h8M7 6h10");
}

</style>
