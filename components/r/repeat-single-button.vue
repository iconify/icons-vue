<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="x-kz1kb7j"/><path class="kt750rbvg"/><circle class="v6xg6nbdp"/><path class="d0crkebso"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:repeat-single-button" /></template>
<style>
.d0crkebso {
  fill: var(--svg-color--3b88c3, #3b88c3);
  d: path("M10.201 23.116h-.708c-.576 0-.815-.42-.815-.828c0-.419.3-.827.815-.827h1.703c.516 0 .804.371.804.852v5.752c0 .6-.384.935-.899.935s-.899-.336-.899-.935z");
}

.kt750rbvg {
  fill: var(--svg-color--fff, #fff);
  d: path("m30.174 14.023l-3.301 2.75q.126.595.127 1.227a6 6 0 0 1-6 6h-1.059q.057.493.059 1c0 1.054-.19 2.06-.523 3H21c5.522 0 10-4.478 10-10a10 10 0 0 0-.826-3.977M30.2 10L23 4v4h-8C9.477 8 5 12.477 5 18c0 .099.012.194.015.292a8.96 8.96 0 0 1 4.273-2.125A6 6 0 0 1 15 12h8v4z");
}

.v6xg6nbdp {
  cx: 11px;
  cy: 25px;
  r: 6px;
  fill: var(--svg-color--fff, #fff);
}

.x-kz1kb7j {
  fill: var(--svg-color--3b88c3, #3b88c3);
  d: path("M36 32a4 4 0 0 1-4 4H4a4 4 0 0 1-4-4V4a4 4 0 0 1 4-4h28a4 4 0 0 1 4 4z");
}

</style>
