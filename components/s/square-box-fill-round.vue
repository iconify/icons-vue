<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d9syg95pm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:square-box-fill-round" /></template>
<style>
.d9syg95pm {
  fill: currentColor;
  d: path("M2 7a5 5 0 0 1 5-5h10a5 5 0 0 1 5 5v10a5 5 0 0 1-1.464 3.536A5 5 0 0 1 17 22H7a5 5 0 0 1-5-5Zm2 10a3 3 0 0 0 3 3h10a3 3 0 0 0 3-3V7a3 3 0 0 0-3-3H7a3 3 0 0 0-3 3Zm4.629-8.335l-1.125-.556q.052-.03.106-.056l.004-.003l3.5-1.728c.27-.133.567-.204.868-.207h.036c.301.003.598.074.868.207l3.5 1.728l.004.003q.054.026.106.056L12 10.329ZM8.5 10.831l2.5 1.235v5.555L7.614 15.95A2 2 0 0 1 6.5 14.161V9.844Zm4.5 1.235l4.5-2.222v4.312c0 .761-.432 1.457-1.114 1.794L13 17.621Z");
}

</style>
