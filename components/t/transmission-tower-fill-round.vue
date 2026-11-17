<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b76_0omoq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:transmission-tower-fill-round" /></template>
<style>
.b76_0omoq {
  fill: currentColor;
  d: path("m5.051 20.684l1-3v-.001L8.613 10H8a3 3 0 0 0-3 3a1 1 0 0 1-2 0a5 5 0 0 1 1.464-3.536A4.98 4.98 0 0 1 8 8h1V7c0-.696.091-1.395.311-2.056c.205-.613.523-1.192.982-1.651a2.414 2.414 0 0 1 3.414 0C14.665 4.252 15 5.683 15 7v1h1c1.33 0 2.597.522 3.536 1.464A5 5 0 0 1 21 13a1 1 0 0 1-2 0a3 3 0 0 0-3-3h-.613l2.561 7.683l.001.002l1 2.999a1.001 1.001 0 0 1-1.898.632L16.279 19H7.721l-.772 2.316a1.001 1.001 0 0 1-1.898-.632M13 8V7c0-.481-.056-.966-.209-1.424c-.106-.318-.259-.63-.498-.869a.413.413 0 0 0-.586 0c-.239.239-.392.551-.498.869A4.5 4.5 0 0 0 11 7v1Zm-1 7.764l1.92-3.841L13.279 10h-2.558l-.641 1.923ZM10.382 17l-1.197-2.393L8.387 17Zm3.236 0h1.995l-.798-2.393Z");
}

</style>
