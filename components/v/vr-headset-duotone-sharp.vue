<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="czax4l6ei"/><path class="rzm8iaclc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:vr-headset-duotone-sharp" /></template>
<style>
.czax4l6ei {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M8 5h8c1.435 0 3.008.206 4.206 1.061C21.51 6.993 22 8.446 22 10v3c0 1.542-.479 3.095-1.491 4.276C19.63 18.301 18.371 19 17 19c-.692 0-1.349-.256-1.913-.647c-.683-.473-1.222-1.109-1.83-1.667C12.92 16.376 12.481 16 12 16s-.92.376-1.257.686c-.608.558-1.147 1.194-1.83 1.667C8.349 18.744 7.692 19 7 19c-1.371 0-2.63-.699-3.509-1.724C2.479 16.095 2 14.542 2 13v-3c0-1.554.49-3.007 1.794-3.939C4.992 5.206 6.565 5 8 5");
}

.ft5dv1b6b {
  fill: none;
}

.rzm8iaclc {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3 10c0-3 2-4 5-4h8c3 0 5 1 5 4v3c0 3-2 5-4 5s-3-3-5-3s-3 3-5 3s-4-2-4-5Z");
}

</style>
