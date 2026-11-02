<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="e0_njybpv"/><path class="pdkoty56j"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:tiktok-bulk-round" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.e0_njybpv {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M17 11.78v2.72a7.5 7.5 0 0 1-6.013 7.351A7.496 7.496 0 0 1 2.59 17.42A7.502 7.502 0 0 1 7.769 7.202A.998.998 0 0 1 9 8.175V12.5a1 1 0 0 1-.4.8a1.456 1.456 0 0 0-.523 1.674c.096.29.271.546.513.732c.262.2.582.294.91.294q.304 0 .584-.117c.556-.235.917-.779.916-1.383V3a1 1 0 0 1 1-1h4a1 1 0 0 1 1 1a3.95 3.95 0 0 0 .314 1.557c.2.475.492.907.858 1.271c.364.366.796.658 1.271.858A3.95 3.95 0 0 0 21 7a1 1 0 0 1 1 1v4a1 1 0 0 1-1.135.991A12.1 12.1 0 0 1 17 11.78");
}

.pdkoty56j {
  d: path("M15 3a1 1 0 0 1 2 0c0 1.065.416 2.078 1.172 2.828c.364.366.796.658 1.271.858A3.95 3.95 0 0 0 21 7a1 1 0 0 1 1 1v4a1 1 0 0 1-1.135.991a12 12 0 0 1-2.859-.755a12 12 0 0 1-2.591-1.425A1 1 0 0 1 15 10Z");
}

</style>
