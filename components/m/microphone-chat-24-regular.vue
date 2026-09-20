<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jvbi8i21h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:microphone-chat-24-regular" /></template>
<style>
.jvbi8i21h {
  fill: currentColor;
  d: path("M21.75 12.75a.75.75 0 0 1 .75.75a6 6 0 0 1-5.25 5.951v1.799a.75.75 0 0 1-1.5 0v-1.799A6 6 0 0 1 10.5 13.5a.75.75 0 0 1 1.5 0a4.5 4.5 0 0 0 9 0a.75.75 0 0 1 .75-.75M10 2a7.97 7.97 0 0 1 5.432 2.128a4.5 4.5 0 0 0-1.513.686a6.5 6.5 0 0 0-9.673 8.205a.75.75 0 0 1 .063.53l-.715 2.86l2.86-.716l.135-.021a.75.75 0 0 1 .395.085a6.5 6.5 0 0 0 3.017.743q.086-.001.172-.005c.244.515.55.994.906 1.43a7.96 7.96 0 0 1-4.527-.712l-2.998.752a1.25 1.25 0 0 1-1.515-1.516l.749-2.998A7.96 7.96 0 0 1 2 10a8 8 0 0 1 8-8m6.5 3A3.5 3.5 0 0 1 20 8.5v5a3.5 3.5 0 0 1-7 0v-5A3.5 3.5 0 0 1 16.5 5m0 1.5a2 2 0 0 0-2 2v5a2 2 0 0 0 4 0v-5a2 2 0 0 0-2-2");
}

</style>
