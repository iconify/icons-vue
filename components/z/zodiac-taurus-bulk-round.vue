<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="asw7adygk"/><path class="bxgsmy3yp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:zodiac-taurus-bulk-round" /></template>
<style>
.asw7adygk {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M7.393 4.946a5 5 0 0 0 9.214 0A4.9 4.9 0 0 0 17 3a1 1 0 0 1 2 0A7.001 7.001 0 0 1 5 3a1 1 0 0 1 2 0a4.9 4.9 0 0 0 .393 1.946");
}

.bxgsmy3yp {
  d: path("M12.001 10a5 5 0 1 0-.002 10A5 5 0 0 0 12 10m-.002-2A7 7 0 1 1 12 22a7 7 0 0 1-.003-14");
}

.cuyn6tgcc {
  fill: currentColor;
}

</style>
