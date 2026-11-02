<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="f-7fx30kx"/><path class="jr6j3fbpn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:more-vertical-duotone-sharp" /></template>
<style>
.f-7fx30kx {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M12 7a1 1 0 1 1 0-2a1 1 0 0 1 0 2m0 6a1 1 0 1 1 0-2a1 1 0 0 1 0 2m0 6a1 1 0 1 1 0-2a1 1 0 0 1 0 2");
}

.ft5dv1b6b {
  fill: none;
}

.jr6j3fbpn {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M11 6a1 1 0 1 0 2 0a1 1 0 0 0-2 0m0 6a1 1 0 1 0 2 0a1 1 0 0 0-2 0m0 6a1 1 0 1 0 2 0a1 1 0 0 0-2 0");
}

</style>
