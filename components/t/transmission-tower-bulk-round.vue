<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="t31wmmlhc"/><path class="hx486fbjg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:transmission-tower-bulk-round" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.hx486fbjg {
  d: path("M8.613 10H8a3 3 0 0 0-3 3a1 1 0 0 1-2 0a5 5 0 0 1 1.464-3.536A4.98 4.98 0 0 1 8 8h1V7c0-.696.091-1.395.311-2.056c.205-.613.523-1.192.982-1.651a2.414 2.414 0 0 1 3.414 0C14.665 4.252 15 5.683 15 7v1h1c1.33 0 2.597.522 3.536 1.464A5 5 0 0 1 21 13a1 1 0 0 1-2 0a3 3 0 0 0-3-3h-.613l3.562 10.684a1.001 1.001 0 0 1-1.898.632L13.279 10h-2.558L6.949 21.316a1.001 1.001 0 0 1-1.898-.632ZM11 8h2V7c0-.481-.056-.966-.209-1.424c-.106-.318-.259-.63-.498-.869a.413.413 0 0 0-.586 0c-.239.239-.392.551-.498.869A4.5 4.5 0 0 0 11 7Z");
}

.t31wmmlhc {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("m12 15.764l2.106-4.211a1 1 0 1 1 1.788.894L13.618 17H17a1 1 0 0 1 0 2H7a1 1 0 0 1 0-2h3.382l-2.276-4.553a1 1 0 1 1 1.788-.894Z");
}

</style>
