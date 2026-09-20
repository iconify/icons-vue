<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<path class="a7lf3mtsh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:video-prohibited-28-regular" /></template>
<style>
.a7lf3mtsh {
  fill: currentColor;
  d: path("M7.5 13a6.5 6.5 0 1 1 0 13a6.5 6.5 0 0 1 0-13M4.534 23.526a5 5 0 0 0 6.992-6.992zM7.5 14.5a5 5 0 0 0-4.026 7.966l6.992-6.992A4.98 4.98 0 0 0 7.5 14.5M15.25 6A3.75 3.75 0 0 1 19 9.75v.499l4.252-2.937c1.16-.8 2.744.03 2.744 1.44v10.491c0 1.41-1.583 2.24-2.744 1.44L19 17.747v.503A3.75 3.75 0 0 1 15.25 22h-.679q.256-.72.36-1.5h.319a2.25 2.25 0 0 0 2.25-2.25v-8.5a2.25 2.25 0 0 0-2.25-2.25h-9.5A2.25 2.25 0 0 0 3.5 9.75v3.407A7.5 7.5 0 0 0 2 14.402V9.75A3.75 3.75 0 0 1 5.75 6zm9.246 2.753a.25.25 0 0 0-.392-.206L19 12.07v3.854l5.104 3.523a.25.25 0 0 0 .392-.205z");
}

</style>
