<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<path class="c4ztywrlv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:microphone-chat-28-regular" /></template>
<style>
.c4ztywrlv {
  fill: currentColor;
  d: path("M25.75 15.25a.75.75 0 0 1 .75.75a7 7 0 0 1-6.25 6.959v2.291a.75.75 0 0 1-1.5 0v-2.291A7 7 0 0 1 12.5 16a.75.75 0 0 1 1.5 0a5.5 5.5 0 0 0 11 0a.75.75 0 0 1 .75-.75M11.5 2c2.78 0 5.28 1.194 7.017 3.097a5 5 0 0 0-1.532.582A7.97 7.97 0 0 0 11.501 3.5a8 8 0 0 0-7.067 11.75c.087.164.11.354.066.534l-.907 3.624l3.623-.906l.137-.021a.75.75 0 0 1 .398.086a7.96 7.96 0 0 0 4.536.894q.359.744.856 1.394a9.46 9.46 0 0 1-5.835-.83l-3.755.94a1.25 1.25 0 0 1-1.515-1.516l.938-3.756a9.46 9.46 0 0 1-.975-4.193C2 6.254 6.254 2 11.5 2m8 4a4 4 0 0 1 4 4v6a4 4 0 0 1-8 0v-6a4 4 0 0 1 4-4m0 1.5A2.5 2.5 0 0 0 17 10v6a2.5 2.5 0 0 0 5 0v-6a2.5 2.5 0 0 0-2.5-2.5");
}

</style>
