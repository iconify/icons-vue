<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="zm7wzhk1b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:text-hanging-20-filled" /></template>
<style>
.zm7wzhk1b {
  fill: currentColor;
  d: path("M3.75 3.5a.75.75 0 0 0 0 1.5h12.5a.75.75 0 0 0 0-1.5zm5 10a.75.75 0 0 0 0 1.5h7.5a.75.75 0 0 0 0-1.5zM8 9.25a.75.75 0 0 1 .75-.75h7.5a.75.75 0 0 1 0 1.5h-7.5A.75.75 0 0 1 8 9.25m-3.72 1.47a.75.75 0 0 0-1.06 1.06l.97.97l-.97.97a.75.75 0 1 0 1.06 1.06l1.5-1.5a.75.75 0 0 0 0-1.06z");
}

</style>
