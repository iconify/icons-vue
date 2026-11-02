<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="wtdkvv6kf"/><path class="t9qmpugdp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:soup-bulk-round" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.t9qmpugdp {
  d: path("m9.894 5.447l-1 2a1 1 0 1 1-1.788-.894l1-2a1 1 0 1 1 1.788.894m4 0l-1 2a1 1 0 1 1-1.788-.894l1-2a1 1 0 1 1 1.788.894m3 2a1 1 0 1 1-1.788-.894l1-2a1 1 0 1 1 1.788.894Zm1.178 3.182l2-5a.998.998 0 1 1 1.856.742l-2 5a.998.998 0 1 1-1.856-.742");
}

.wtdkvv6kf {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M3 10h18a1 1 0 0 1 1 1c0 5.523-4.477 10-10 10S2 16.523 2 11a1 1 0 0 1 1-1");
}

</style>
