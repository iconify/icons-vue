<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="v46c5sbaj"/><path class="wk5_g0bod"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:shield-warning-duotone-round" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.v46c5sbaj {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M12 3h4a4 4 0 0 1 4 4v3c-.003 5.351-3.324 8.92-8 11c-4.676-2.08-7.997-5.649-8-11V7a4 4 0 0 1 4-4Z");
}

.wk5_g0bod {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 3h4a4 4 0 0 1 4 4v3c0 5.5-3.5 9-8 11c-4.5-2-8-5.5-8-11V7a4 4 0 0 1 4-4zm0 5v4m0 3h.01");
}

</style>
