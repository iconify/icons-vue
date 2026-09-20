<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zcu54wbro"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:markdown-24-filled" /></template>
<style>
.zcu54wbro {
  fill: currentColor;
  d: path("M19 5a1 1 0 0 1 1 1v8.588l.796-.795a1 1 0 1 1 1.414 1.414l-2.501 2.502a1 1 0 0 1-1.414 0l-2.502-2.502a1 1 0 1 1 1.414-1.414l.793.793V6a1 1 0 0 1 1-1m-6.74.327A1 1 0 0 1 14 6v11a1 1 0 1 1-2 0V8.587l-3.26 3.586a1 1 0 0 1-1.48 0L4 8.587V17a1 1 0 1 1-2 0V6a1 1 0 0 1 1.74-.673L8 10.013z");
}

</style>
