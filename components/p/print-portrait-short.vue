<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m3v1o0bgw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:print-portrait-short" /></template>
<style>
.m3v1o0bgw {
  fill: currentColor;
  d: path("M4.804 16.192q-.82 0-1.304-.66t-.17-1.418q.649-1.608 1.443-3.882t.973-4.774q.056-.627.474-1.043Q6.64 4 7.246 4h.383V3H9.32v1h5.102V3h1.693v1q.805 0 1.335.52t.53 1.326q0 .825-.328 2.095t-.802 2.62t-1.02 2.6t-.96 2.035q-.248.46-.667.728t-.937.268zM7.379 20q-.69 0-1.153-.462t-.462-1.153v-1.231h7.503q.783 0 1.436-.396t1.02-1.092q.618-1.222 1.202-2.567t1.056-2.801v8.087q0 .69-.463 1.153T16.366 20z");
}

</style>
