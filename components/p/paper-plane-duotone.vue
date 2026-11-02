<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="jyg_17uzr"/><path class="xo4m92bbn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:paper-plane-duotone" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.jyg_17uzr {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M17.684 3.051a2.582 2.582 0 0 1 3.265 3.265l-4 12a3.2 3.2 0 0 1-.609 1.066c-.506.584-1.28 1.041-2.077.917a1.56 1.56 0 0 1-1.157-.852l-2.851-5.702l-5.702-2.851a1.56 1.56 0 0 1-.852-1.157c-.124-.797.333-1.571.917-2.077a3.2 3.2 0 0 1 1.066-.609Z");
}

.xo4m92bbn {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 6L6 8c-1.107.369-1.738 1.631-1 2l6 3l3 6c.369.738 1.631.107 2-1l4-12c.412-1.236-.764-2.412-2-2zm-1 7l3-3");
}

</style>
