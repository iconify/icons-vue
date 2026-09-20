<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="hyapw8b0i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:text-bullet-list-checkmark-20-regular" /></template>
<style>
.hyapw8b0i {
  fill: currentColor;
  d: path("M3 5.5a1 1 0 1 0 0-2a1 1 0 0 0 0 2m3-1a.5.5 0 0 1 .5-.5h11a.5.5 0 0 1 0 1h-11a.5.5 0 0 1-.5-.5m0 5a.5.5 0 0 1 .5-.5h11a.5.5 0 0 1 0 1h-11a.5.5 0 0 1-.5-.5m4.022 5.5q.047-.516.185-1H6.5a.5.5 0 0 0 0 1zM4 14.5a1 1 0 1 1-2 0a1 1 0 0 1 2 0m-1-4a1 1 0 1 0 0-2a1 1 0 0 0 0 2m17 5a4.5 4.5 0 1 1-9 0a4.5 4.5 0 0 1 9 0m-5.5.793l-.646-.647a.5.5 0 0 0-.708.708l1 1a.5.5 0 0 0 .708 0l3-3a.5.5 0 0 0-.708-.708z");
}

</style>
