<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="lx7bfib9r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:table-cell-add-20-regular" /></template>
<style>
.lx7bfib9r {
  fill: currentColor;
  d: path("M14.5 10a4.5 4.5 0 1 1 0 9a4.5 4.5 0 0 1 0-9M11 2a2 2 0 0 1 2 2v3h3a2 2 0 0 1 2 2v1.257a5.5 5.5 0 0 0-1-.656V9a1 1 0 0 0-1-1h-3v1.208a5.5 5.5 0 0 0-1 .393V8H8v4h1.602a5.5 5.5 0 0 0-.394 1H8v3a1 1 0 0 0 1 1h.602q.274.538.656 1H9a2 2 0 0 1-2-2v-3H4a2 2 0 0 1-2-2V9a2 2 0 0 1 2-2h3V4a2 2 0 0 1 2-2zm3.5 10a.5.5 0 0 0-.5.5V14h-1.5a.5.5 0 0 0 0 1H14v1.5a.5.5 0 0 0 1 0V15h1.5a.5.5 0 0 0 0-1H15v-1.5a.5.5 0 0 0-.5-.5M4 8a1 1 0 0 0-1 1v2a1 1 0 0 0 1 1h3V8zm5-5a1 1 0 0 0-1 1v3h4V4a1 1 0 0 0-1-1z");
}

</style>
