<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xmj310tzl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:table-freeze-row-24-filled" /></template>
<style>
.xmj310tzl {
  fill: currentColor;
  d: path("M6.25 3A3.25 3.25 0 0 0 3 6.25v8.25h5v-5H4.5V6.25c0-.966.784-1.75 1.75-1.75h11.5c.966 0 1.75.784 1.75 1.75V9.5H16v5h5V6.25A3.25 3.25 0 0 0 17.75 3zM21 16h-5v5h1.75A3.25 3.25 0 0 0 21 17.75zm-6.5-1.5v-5h-5v5zm-5 1.5h5v5h-5zM8 16H3v1.75A3.25 3.25 0 0 0 6.25 21H8z");
}

</style>
