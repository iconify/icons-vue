<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="f10690buu"/><path class="k2e2ugbgc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:shield-sparkle-duotone-sharp" /></template>
<style>
.f10690buu {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M20 3v7c-.003 5.351-3.324 8.92-8 11c-4.676-2.08-7.997-5.649-8-11V3Z");
}

.ft5dv1b6b {
  fill: none;
}

.k2e2ugbgc {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 3h8v7c0 5.5-3.5 9-8 11c-4.5-2-8-5.5-8-11V3zm0 4c0 2 2 4 4 4c-2 0-4 2-4 4c0-2-2-4-4-4c2 0 4-2 4-4");
}

</style>
