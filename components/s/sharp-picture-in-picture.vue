<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ro3u7ld2q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-picture-in-picture" /></template>
<style>
.ro3u7ld2q {
  fill: currentColor;
  d: path("M19 7h-8v6h8zm4-4H1v17.98h22zm-2 16.01H3V4.98h18z");
}

</style>
