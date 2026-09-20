<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="utpxc3vdl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:window-new-24-filled" /></template>
<style>
.utpxc3vdl {
  fill: currentColor;
  d: path("M17.75 3A3.25 3.25 0 0 1 21 6.25v8.5a3.25 3.25 0 0 1-3.01 3.24A3.25 3.25 0 0 1 14.75 21h-6A5.75 5.75 0 0 1 3 15.25v-6a3.25 3.25 0 0 1 3.009-3.241A3.25 3.25 0 0 1 9.25 3zM6 7.52c-.848.121-1.5.848-1.5 1.73v6a4.25 4.25 0 0 0 4.25 4.25h6c.882 0 1.61-.652 1.73-1.5H9.25A3.25 3.25 0 0 1 6 14.75zM11.75 7a.75.75 0 0 0 0 1.5h2.69l-4.22 4.22a.75.75 0 0 0 1.06 1.06l4.22-4.22v2.69a.75.75 0 0 0 1.5 0v-4.5a.75.75 0 0 0-.75-.75z");
}

</style>
