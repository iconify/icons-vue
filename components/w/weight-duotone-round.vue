<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="hs5pvc9mx"/><path class="ukvl-hhfo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:weight-duotone-round" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.hs5pvc9mx {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M14 7c1.73 0 3.388 1.003 3.949 2.684l2 6c.635 1.906-.259 3.95-2.033 4.858A4.16 4.16 0 0 1 16 21H8a4.16 4.16 0 0 1-1.916-.458c-1.774-.908-2.668-2.952-2.033-4.858l2-6c.228-.683.581-1.327 1.093-1.839C7.637 7.352 8.29 7 9 7Z");
}

.ukvl-hhfo {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 8h2c1.393 0 2.602.806 3 2l2 6c.656 1.968-.868 4-3 4H8c-2.132 0-3.656-2.032-3-4l2-6c.398-1.194 1.204-2 2-2zm0 0a2 2 0 1 1 0-4m0 0a2 2 0 1 1 0 4");
}

</style>
