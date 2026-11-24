<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="izjp3jzni"/><path class="qir4pccvn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:silo-duotone-sharp" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.izjp3jzni {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M4 8a4 4 0 0 1 8 0v13H4Z");
}

.qir4pccvn {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M4 21V8a4 4 0 1 1 8 0v13m-9 0h18M12 8l8 4v9M4 13h8m-8 4h8");
}

</style>
