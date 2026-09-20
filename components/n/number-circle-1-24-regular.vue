<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bv4s04kzq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:number-circle-1-24-regular" /></template>
<style>
.bv4s04kzq {
  fill: currentColor;
  d: path("M13.5 7.25a.75.75 0 0 0-1.485-.147c-.096.478-.404 1.12-.879 1.706c-.474.586-1.051 1.039-1.623 1.23a.75.75 0 0 0 .474 1.422c.778-.259 1.465-.773 2.013-1.36v6.149a.75.75 0 0 0 1.5 0zM12 2C6.477 2 2 6.477 2 12s4.477 10 10 10s10-4.477 10-10S17.523 2 12 2M3.5 12a8.5 8.5 0 1 1 17 0a8.5 8.5 0 0 1-17 0");
}

</style>
