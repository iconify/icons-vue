<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="bwnfvccbk"/><path class="cyld6dbjy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:package-download-duotone-round" /></template>
<style>
.bwnfvccbk {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M4.106 5.553C4.848 4.069 6.307 3 8 3h8c1.693 0 3.152 1.069 3.894 2.553l1 2A1 1 0 0 1 20 9H4a1 1 0 0 1-.894-1.447Z");
}

.cyld6dbjy {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M5 6c.613-1.226 1.774-2 3-2h8c1.226 0 2.387.774 3 2l1 2v8a4 4 0 0 1-4 4H8a4 4 0 0 1-4-4V8zM4 8h16M9 14l3 3l3-3m-3 3v-6");
}

.ft5dv1b6b {
  fill: none;
}

</style>
