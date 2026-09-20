<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w35v5ql2q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:video-clip-optimize-24-filled" /></template>
<style>
.w35v5ql2q {
  fill: currentColor;
  d: path("M3.5 7.75A4.25 4.25 0 0 1 7.75 3.5h.5a.75.75 0 0 0 0-1.5h-.5A5.75 5.75 0 0 0 2 7.75v.5a.75.75 0 0 0 1.5 0zm0 8.5a4.25 4.25 0 0 0 4.25 4.25h.5a.75.75 0 0 1 0 1.5h-.5A5.75 5.75 0 0 1 2 16.25v-.5a.75.75 0 0 1 1.5 0zM16.25 3.5a4.25 4.25 0 0 1 4.25 4.25v.5a.75.75 0 0 0 1.5 0v-.5A5.75 5.75 0 0 0 16.25 2h-.5a.75.75 0 0 0 0 1.5zm4.25 12.75a4.25 4.25 0 0 1-4.25 4.25h-.5a.75.75 0 0 0 0 1.5h.5A5.75 5.75 0 0 0 22 16.25v-.5a.75.75 0 0 0-1.5 0zM8.25 5A3.25 3.25 0 0 0 5 8.25v7.5A3.25 3.25 0 0 0 8.25 19h7.5A3.25 3.25 0 0 0 19 15.75v-7.5A3.25 3.25 0 0 0 15.75 5zM9 14.75v-5.5a1 1 0 0 1 1.482-.876l5 2.75a1 1 0 0 1 0 1.753l-5 2.75A1 1 0 0 1 9 14.75");
}

</style>
