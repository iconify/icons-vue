<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="w3kb-jhyo"/><path class="sojv_8bkw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:shield-user-duotone" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.sojv_8bkw {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 3h6a2 2 0 0 1 2 2v5c0 5.5-3.5 9-8 11c-4.5-2-8-5.5-8-11V5a2 2 0 0 1 2-2zm-2 6a2 2 0 1 0 4 0a2 2 0 0 0-4 0m-2 9a4.167 4.167 0 0 1 8 0");
}

.w3kb-jhyo {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M18 2a3 3 0 0 1 3 3v5c-.001 5.712-3.495 9.647-8.594 11.914a1 1 0 0 1-.812 0C6.495 19.647 3.001 15.712 3 10V5a3 3 0 0 1 3-3Z");
}

</style>
