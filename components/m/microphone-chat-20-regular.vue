<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="g11s6ksnn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:microphone-chat-20-regular" /></template>
<style>
.g11s6ksnn {
  fill: currentColor;
  d: path("M18.5 10.5a.5.5 0 0 1 .5.5a5 5 0 0 1-4.5 4.975V17.5a.5.5 0 1 1-1 0v-1.525A5 5 0 0 1 9 11a.5.5 0 0 1 1 0a4 4 0 0 0 8 0a.5.5 0 0 1 .5-.5M8.502 2c1.475 0 2.836.493 3.927 1.321a4 4 0 0 0-.937.564a5.5 5.5 0 0 0-7.878 7.139a.5.5 0 0 1 .04.35l-.653 2.621l2.617-.655a.5.5 0 0 1 .352.042a5.5 5.5 0 0 0 2.83.61q.29.501.666.936a6.47 6.47 0 0 1-3.78-.574l-2.442.612a1 1 0 0 1-1.213-1.213l.61-2.447a6.5 6.5 0 0 1-.64-2.806a6.5 6.5 0 0 1 6.5-6.5M14 4a3 3 0 0 1 3 3v4a3 3 0 1 1-6 0V7a3 3 0 0 1 3-3m0 1a2 2 0 0 0-2 2v4a2 2 0 0 0 4 0V7a2 2 0 0 0-2-2");
}

</style>
