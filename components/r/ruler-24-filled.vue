<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rxve8hbit"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:ruler-24-filled" /></template>
<style>
.rxve8hbit {
  fill: currentColor;
  d: path("M7 4.25A2.25 2.25 0 0 1 9.25 2h5.5A2.25 2.25 0 0 1 17 4.25v15.5A2.25 2.25 0 0 1 14.75 22h-5.5q-.233 0-.453-.046A2.25 2.25 0 0 1 7 19.75zM8.5 5v1.5h1.75a.75.75 0 0 0 0-1.5zm0 3v1.5h3.75a.75.75 0 0 0 0-1.5zm0 3.25v1.5h1.75a.75.75 0 0 0 0-1.5zm0 3.25V16h3.75a.75.75 0 0 0 0-1.5zm0 3V19h1.75a.75.75 0 0 0 0-1.5z");
}

</style>
