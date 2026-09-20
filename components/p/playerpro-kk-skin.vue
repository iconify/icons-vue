<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="y9tr6bcfx"><path class="y0su0qnac"/><path class="r_9ll42bg"/></g><path class="bc4y1pbur"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:playerpro-kk-skin" /></template>
<style>
.bc4y1pbur {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M9.77 7.635a2.135 2.135 0 1 1-4.27 0a2.135 2.135 0 0 1 4.27 0m-.657 1.539L6.096 6.156M9.77 40.365a2.135 2.135 0 0 1-4.27 0a2.135 2.135 0 0 1 4.27 0m-.596-1.478l-3.018 3.017M42.5 7.635a2.135 2.135 0 0 1-4.27 0a2.135 2.135 0 1 1 4.27 0m-3.613 1.539l3.017-3.018m.596 34.209a2.135 2.135 0 0 1-4.27 0a2.135 2.135 0 0 1 4.27 0m-3.674-1.478l3.018 3.017M33.762 24.4c.549-.55.69-1.383.35-2.081a19 19 0 0 0-3.482-4.95a16.8 16.8 0 0 0-4.988-3.518a1.805 1.805 0 0 0-2.031.373l-6.034 6.034c-.71.71-.71 1.861 0 2.57l2.535 2.536l-3.789 3.789c-.683.683-.784 1.807-.137 2.524c.69.766 1.87.789 2.589.07l3.86-3.86l2.534 2.535c.71.71 1.861.71 2.571 0zm-14.016-6.31l10.163 10.163");
}

.r_9ll42bg {
  d: path("M38.705 24c0 8.121-6.584 14.705-14.705 14.705S9.295 32.121 9.295 24S15.879 9.295 24 9.295S38.705 15.879 38.705 24");
}

.y0su0qnac {
  d: path("M42.5 24c0 10.217-8.283 18.5-18.5 18.5S5.5 34.217 5.5 24S13.783 5.5 24 5.5S42.5 13.783 42.5 24");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
