<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="bpp7y5g_r"/><path class="gi6zkc04d"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:square-sparkle-bulk-sharp" /></template>
<style>
.bpp7y5g_r {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M2 3a1 1 0 0 1 1-1h18a1 1 0 0 1 1 1v18a1 1 0 0 1-1 1H3a1 1 0 0 1-1-1Z");
}

.cuyn6tgcc {
  fill: currentColor;
}

.gi6zkc04d {
  d: path("M6 12a1 1 0 0 1 1-1c.574 0 1.151-.086 1.688-.293a3.5 3.5 0 0 0 1.23-.789c.348-.348.613-.771.789-1.23A4.7 4.7 0 0 0 11 7a1 1 0 0 1 2 0c0 .574.086 1.151.293 1.688c.176.459.441.882.789 1.23s.771.613 1.23.789A4.7 4.7 0 0 0 17 11a1 1 0 0 1 0 2c-.574 0-1.151.086-1.688.293a3.5 3.5 0 0 0-1.23.789a3.5 3.5 0 0 0-.789 1.23A4.7 4.7 0 0 0 13 17a1 1 0 0 1-2 0c0-.574-.086-1.151-.293-1.688a3.5 3.5 0 0 0-.789-1.23a3.5 3.5 0 0 0-1.23-.789A4.7 4.7 0 0 0 7 13a1 1 0 0 1-1-1");
}

</style>
