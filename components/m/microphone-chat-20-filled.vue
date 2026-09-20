<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="d2_mkdb-z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:microphone-chat-20-filled" /></template>
<style>
.d2_mkdb-z {
  fill: currentColor;
  d: path("M18.5 10.5a.5.5 0 0 1 .5.5a5 5 0 0 1-4.5 4.975V17.5a.5.5 0 0 1-1 0v-1.525A5 5 0 0 1 9 11a.5.5 0 0 1 1 0a4 4 0 0 0 8 0a.5.5 0 0 1 .5-.5M8.5 2c1.476 0 2.836.492 3.927 1.32A4 4 0 0 0 10 7v2.587A1.498 1.498 0 0 0 8 11a5.98 5.98 0 0 0 1.465 3.928a6.47 6.47 0 0 1-3.78-.574l-2.441.612a1 1 0 0 1-1.213-1.213l.61-2.447a6.5 6.5 0 0 1-.64-2.806a6.5 6.5 0 0 1 6.5-6.5M14 4a3 3 0 0 1 3 3v4a3 3 0 0 1-6 0V7a3 3 0 0 1 3-3");
}

</style>
