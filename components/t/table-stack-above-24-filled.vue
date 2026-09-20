<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b29xl16bt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:table-stack-above-24-filled" /></template>
<style>
.b29xl16bt {
  fill: currentColor;
  d: path("M20.25 4.5a.75.75 0 0 0 0-1.5H3.75a.75.75 0 0 0 0 1.5zm-5.75 5v5h-5v-5zm-5 6.5h5v5h-5zM8 9.5v5H3v-4.25a.75.75 0 0 1 .75-.75zM8 16H3v1.75A3.25 3.25 0 0 0 6.25 21H8zm13 0h-5v5h1.75A3.25 3.25 0 0 0 21 17.75zm-5-1.5h5v-4.25a.75.75 0 0 0-.75-.75H16z");
}

</style>
