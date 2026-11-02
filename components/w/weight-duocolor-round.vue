<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="qdy_ubbsn"/><path class="yj0guvgum"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:weight-duocolor-round" /></template>
<style>
.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.qdy_ubbsn {
  stroke-opacity: 0.4;
  d: path("M12 8a2 2 0 1 1 0-4m0 0a2 2 0 1 1 0 4");
}

.yj0guvgum {
  d: path("M12 8h2c1.393 0 2.602.806 3 2l2 6c.656 1.968-.868 4-3 4H8c-2.132 0-3.656-2.032-3-4l2-6c.398-1.194 1.204-2 2-2z");
}

</style>
