<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="nihrfwb9j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:table-simple-exclude-32-filled" /></template>
<style>
.nihrfwb9j {
  fill: currentColor;
  d: path("M6.5 2H12v10H2V6.5A4.5 4.5 0 0 1 6.5 2M2 14v5a4.5 4.5 0 0 0 4.5 4.5H12V14zm21.5-2V6.5A4.5 4.5 0 0 0 19 2h-5v10zM16 19a3 3 0 0 1 3-3h8a3 3 0 0 1 3 3v8a3 3 0 0 1-3 3h-8a3 3 0 0 1-3-3z");
}

</style>
