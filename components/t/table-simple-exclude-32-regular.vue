<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="smi63vj7o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:table-simple-exclude-32-regular" /></template>
<style>
.smi63vj7o {
  fill: currentColor;
  d: path("M6.5 2A4.5 4.5 0 0 0 2 6.5V19a4.5 4.5 0 0 0 4.5 4.5H13a1 1 0 0 0 1-1V14h8.5a1 1 0 0 0 1-1V6.5A4.5 4.5 0 0 0 19 2zM12 14v7.5H6.5A2.5 2.5 0 0 1 4 19v-5zm0-2H4V6.5A2.5 2.5 0 0 1 6.5 4H12zm2 0V4h5a2.5 2.5 0 0 1 2.5 2.5V12zm2 7a3 3 0 0 1 3-3h8a3 3 0 0 1 3 3v8a3 3 0 0 1-3 3h-8a3 3 0 0 1-3-3z");
}

</style>
