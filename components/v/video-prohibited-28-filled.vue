<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<path class="lugg5qblw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:video-prohibited-28-filled" /></template>
<style>
.lugg5qblw {
  fill: currentColor;
  d: path("M7.5 13a6.5 6.5 0 1 1 0 13a6.5 6.5 0 0 1 0-13M4.534 23.526a5 5 0 0 0 6.992-6.992zM7.5 14.5a5 5 0 0 0-4.026 7.966l6.992-6.992A4.98 4.98 0 0 0 7.5 14.5M14.25 6A3.75 3.75 0 0 1 18 9.75v8.5a3.75 3.75 0 0 1-3.424 3.734A7.5 7.5 0 0 0 2 14.402V9.75A3.75 3.75 0 0 1 5.75 6zm9.002 1.313c1.16-.801 2.744.03 2.744 1.44v10.49c0 1.41-1.583 2.24-2.744 1.44L19 17.747V10.25z");
}

</style>
