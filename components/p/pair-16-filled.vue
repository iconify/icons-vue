<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="acz9qypxt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:pair-16-filled" /></template>
<style>
.acz9qypxt {
  fill: currentColor;
  d: path("M9.75 1.25a1.5 1.5 0 0 1 .75 2.798V5.5h1.452A1.498 1.498 0 1 1 14 7.548v4.403A1.499 1.499 0 1 1 11.952 14H7.548a1.498 1.498 0 0 1-2.798-.75a1.5 1.5 0 0 1 .75-1.299V10.5H4.048a1.498 1.498 0 0 1-2.798-.75A1.5 1.5 0 0 1 2 8.451V4.048A1.498 1.498 0 1 1 4.048 2h4.404c.26-.448.743-.75 1.298-.75m.75 7.201A1.5 1.5 0 1 1 8.452 10.5H7v1.451c.227.132.416.322.548.549h4.404a1.5 1.5 0 0 1 .548-.549V7.548A1.5 1.5 0 0 1 11.952 7H10.5zM7.548 7c-.132.227-.32.416-.548.548V9h1.452A1.5 1.5 0 0 1 9 8.451V7zm-3.5-3.5c-.132.227-.32.416-.548.548V8.45c.227.132.416.322.548.549H5.5V7.548A1.498 1.498 0 1 1 7.548 5.5H9V4.048a1.5 1.5 0 0 1-.548-.548z");
}

</style>
