<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="r90lr0bme"/><path class="v8-icuurm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:zap-duotone-round" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.r90lr0bme {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M12.293 3.293c.31-.311.752-.456 1.186-.382C14.428 3.072 15 4.102 15 5v4a.997.997 0 0 0 1 1h2c.898 0 1.928.572 2.089 1.521a1.34 1.34 0 0 1-.382 1.186l-8 8a1.36 1.36 0 0 1-1.186.382C9.572 20.928 9 19.898 9 19v-4a.997.997 0 0 0-1-1H6c-.898 0-1.928-.572-2.089-1.521a1.34 1.34 0 0 1 .382-1.186Z");
}

.v8-icuurm {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("m9 8l-4 4c-.369.369.262 1 1 1h2a2 2 0 0 1 2 2v4c0 .738.631 1.369 1 1l8-8c.369-.369-.262-1-1-1h-2a2 2 0 0 1-2-2V5c0-.738-.631-1.369-1-1z");
}

</style>
