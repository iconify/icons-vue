<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="kul-web8a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:poll-off-32-regular" /></template>
<style>
.kul-web8a {
  fill: currentColor;
  d: path("m27.165 28.58l1.128 1.127a1 1 0 0 0 1.414-1.414l-26-26a1 1 0 0 0-1.414 1.414L12 13.415V25.5a3.5 3.5 0 1 0 7 0v-5.086l3 3V25.5a3.5 3.5 0 0 0 5.165 3.08m-1.581-1.582L24 25.414v.086a1.5 1.5 0 0 0 1.584 1.498M17 18.415V25.5a1.5 1.5 0 0 1-3 0V15.415zM17 6.5v6.966l2 2V6.5a3.5 3.5 0 1 0-7 0v1.966l2 2V6.5a1.5 1.5 0 0 1 3 0m5 11.965l2 2V12.5a1.5 1.5 0 0 1 3 0v10.965l2 2V12.5a3.5 3.5 0 1 0-7 0zM5.5 15A3.5 3.5 0 0 0 2 18.5v7a3.5 3.5 0 0 0 7 0v-7A3.5 3.5 0 0 0 5.5 15M4 18.5a1.5 1.5 0 0 1 3 0v7a1.5 1.5 0 0 1-3 0z");
}

</style>
