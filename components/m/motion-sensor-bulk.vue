<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="pf4dfybmy"/><path class="tysdnbtxo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:motion-sensor-bulk" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.pf4dfybmy {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M7 3h10a1 1 0 0 1 1 1a5.9 5.9 0 0 1-.472 2.336a6 6 0 0 1-1.285 1.907A5.98 5.98 0 0 1 12 10a5.97 5.97 0 0 1-4.243-1.757a6 6 0 0 1-1.285-1.907A5.9 5.9 0 0 1 6 4a1 1 0 0 1 1-1");
}

.tysdnbtxo {
  d: path("M4 3h16a1.002 1.002 0 0 1 .866 1.5A1 1 0 0 1 20 5H4a1 1 0 1 1 0-2m14.384 8.077l.003.001A1 1 0 0 1 18.6 12.8a10.9 10.9 0 0 1-3.162 1.65a10.98 10.98 0 0 1-6.875 0A10.9 10.9 0 0 1 5.4 12.8a1 1 0 0 1 1.2-1.6a9 9 0 0 0 2.587 1.35a9.03 9.03 0 0 0 6.381-.286A9 9 0 0 0 17.4 11.2a1 1 0 0 1 .984-.123m3.001 4l.002.001A1 1 0 0 1 21.6 16.8a15.9 15.9 0 0 1-4.6 2.4a15.9 15.9 0 0 1-5 .8a15.97 15.97 0 0 1-9.6-3.2a1 1 0 0 1 1.2-1.6q.687.515 1.431.944q.717.413 1.478.736a14 14 0 0 0 9.866.42a13.9 13.9 0 0 0 4.025-2.1c.283-.212.658-.259.985-.123");
}

</style>
