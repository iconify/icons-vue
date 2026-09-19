<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qotui7jgj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-folder-delete" /></template>
<style>
.qotui7jgj {
  fill: currentColor;
  d: path("M22 6v14H2V4h8l2 2zm-5.5 4V9h-2v1H12v1.5h1V17h5v-5.5h1V10zm0 5.5h-2v-4h2z");
}

</style>
