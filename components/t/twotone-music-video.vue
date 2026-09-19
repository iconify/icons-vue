<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rdjaszb7h"/><path class="qlxi02wsf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-music-video" /></template>
<style>
.qlxi02wsf {
  fill: currentColor;
  d: path("M21 3H3c-1.1 0-2 .9-2 2v14c0 1.1.9 2 2 2h18c1.1 0 2-.9 2-2V5c0-1.1-.9-2-2-2m0 16H3V5h18zm-10-1c1.65 0 2.98-1.33 3-2.97V8h3V6h-5v6.18c-.31-.11-.65-.18-1-.18c-1.66 0-3 1.34-3 3s1.34 3 3 3");
}

.rdjaszb7h {
  fill: currentColor;
  d: path("M3 19h18V5H3zm8-7c.35 0 .69.07 1 .18V6h5v2h-3v7.03A3.003 3.003 0 0 1 11 18c-1.66 0-3-1.34-3-3s1.34-3 3-3");
  opacity: var(--svg-opacity--0-3, 0.3);
}

</style>
