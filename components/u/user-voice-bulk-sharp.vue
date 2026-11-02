<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="ig83ifhpq"/><path class="t763__3dc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:user-voice-bulk-sharp" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.ig83ifhpq {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M4 7a5 5 0 1 1 10.001.001A5 5 0 0 1 4 7m11 15H3a1 1 0 0 1-1-1a6.9 6.9 0 0 1 .551-2.725A6.9 6.9 0 0 1 4.05 16.05A6.97 6.97 0 0 1 9 14c1.862 0 3.636.731 4.95 2.05a6.9 6.9 0 0 1 1.499 2.225c.366.862.554 1.789.551 2.725a1 1 0 0 1-1 1");
}

.t763__3dc {
  d: path("M21.255 3.457a10.82 10.82 0 0 1-.341 7.949a1 1 0 1 1-1.828-.812q.15-.337.272-.685A8.8 8.8 0 0 0 19.849 7a8.75 8.75 0 0 0-.763-3.594a1.001 1.001 0 0 1 1.828-.812q.19.425.341.863m-5.149 6.096l.002-.005c.8-1.604.8-3.49.001-5.095l-.002-.003l-.001-.003a.999.999 0 1 1 1.788-.894A7.6 7.6 0 0 1 18.708 7a7.6 7.6 0 0 1-.813 3.447a1 1 0 0 1-1.79-.894ZM2 21a7 7 0 1 1 14 0a1 1 0 0 1-2 0a5.001 5.001 0 0 0-10 0a1 1 0 0 1-2 0");
}

</style>
