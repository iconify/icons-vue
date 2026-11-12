<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n4p2jccec"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:print-portrait-short-outline" /></template>
<style>
.n4p2jccec {
  fill: currentColor;
  d: path("M17.039 5H7.251zM4.801 15.192h8.5q.212 0 .394-.105q.183-.106.279-.298q.5-.933 1.51-3.223t1.496-5.72q.038-.327-.183-.587T16.231 5H7.252q-.212 0-.346.144q-.135.144-.154.356q-.185 2.598-1.013 4.97t-1.456 3.953q-.097.27.057.52t.462.25M7.379 20q-.69 0-1.153-.462t-.462-1.153v-2.693h1v2.693q0 .269.172.442q.173.173.443.173h8.987q.269 0 .442-.173t.173-.442V5.846h1v12.539q0 .69-.463 1.153T16.366 20zm-2.575-3.808q-.82 0-1.304-.66t-.17-1.418q.649-1.608 1.443-3.882t.973-4.774q.056-.627.474-1.043Q6.64 4 7.246 4h.383V3H9.32v1h5.102V3h1.693v1q.805 0 1.335.52t.53 1.326q0 .825-.328 2.095t-.802 2.62t-1.02 2.6t-.96 2.035q-.248.46-.667.728t-.937.268z");
}

</style>
