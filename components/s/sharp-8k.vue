<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j9m617wns"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-8k" /></template>
<style>
.j9m617wns {
  fill: currentColor;
  d: path("M8 12.5h1.5V14H8zM8 10h1.5v1.5H8zm13-7H3v18h18zm-10 7v4c0 .55-.45 1-1 1H7.5c-.55 0-1-.45-1-1v-4c0-.55.45-1 1-1H10c.55 0 1 .45 1 1m7 5h-1.75l-1.75-2.25V15H13V9h1.5v2.25L16.25 9H18l-2.25 3z");
}

</style>
