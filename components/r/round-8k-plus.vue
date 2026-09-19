<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jrm9sf4yh"/><path class="y75a7wwxk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:round-8k-plus" /></template>
<style>
.jrm9sf4yh {
  fill: currentColor;
  d: path("M19 3H5c-1.1 0-2 .9-2 2v14c0 1.1.9 2 2 2h14c1.1 0 2-.9 2-2V5c0-1.1-.9-2-2-2m-9 11c0 .55-.45 1-1 1H7c-.55 0-1-.45-1-1v-4c0-.55.45-1 1-1h2c.55 0 1 .45 1 1zm4.59 1c-.22 0-.42-.1-.55-.27l-1.54-1.98v1.55c0 .39-.31.7-.7.7h-.1c-.39 0-.7-.31-.7-.7V9.7c0-.39.31-.7.7-.7h.09c.39 0 .7.31.7.7v1.55l1.54-1.98c.14-.17.35-.27.56-.27c.58 0 .91.66.56 1.12L13.75 12l1.41 1.88c.34.46.01 1.12-.57 1.12M19 12.5h-1.5V14h-1v-1.5H15v-1h1.5V10h1v1.5H19z");
}

.y75a7wwxk {
  fill: currentColor;
  d: path("M7.5 12.5h1V14h-1zm0-2.5h1v1.5h-1z");
}

</style>
