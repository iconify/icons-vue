<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ja-1acbli"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:midi-off-24-regular" /></template>
<style>
.ja-1acbli {
  fill: currentColor;
  d: path("M2.22 2.22a.75.75 0 0 1 1.06 0l18.5 18.5a.75.75 0 0 1-1.06 1.06L18.94 20H4.25A2.25 2.25 0 0 1 2 17.75V6.25a2.25 2.25 0 0 1 1.2-1.99l-.98-.98a.75.75 0 0 1 0-1.06M19.75 4A2.25 2.25 0 0 1 22 6.25v11.5c0 .315-.065.614-.182.886L20.5 17.317V12H18v2.817l-1.5-1.5V12h-1.317l-1.5-1.5H20.5V6.25a.75.75 0 0 0-.75-.75H8.683L7.183 4zM3.5 17.75c0 .414.336.75.75.75h13.19l-2.94-2.94v.69a.75.75 0 0 1-1.5 0v-2.19l-2-2v4.19a.75.75 0 0 1-1.5 0V12h-2v4.25a.75.75 0 0 1-1.5 0V12H3.5zM4.25 5.5a.75.75 0 0 0-.75.75v4.25h5.94L6.996 8.058A.999.999 0 1 1 5.94 7.002L4.44 5.5zm13 1.5a.75.75 0 0 1 0 1.5h-2.5a.75.75 0 0 1 0-1.5z");
}

</style>
