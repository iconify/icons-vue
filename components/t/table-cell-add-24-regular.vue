<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="khthxeb4v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:table-cell-add-24-regular" /></template>
<style>
.khthxeb4v {
  fill: currentColor;
  d: path("M17.5 12a5.5 5.5 0 1 1 0 11a5.5 5.5 0 0 1 0-11M13.75 2A2.25 2.25 0 0 1 16 4.25V8h3.75A2.25 2.25 0 0 1 22 10.25v2.562a6.5 6.5 0 0 0-1.5-1.079V10.25a.75.75 0 0 0-.75-.75H16v1.676a6.5 6.5 0 0 0-1.5.557V9.5h-5v5h2.233a6.5 6.5 0 0 0-.557 1.5H9.5v3.75c0 .414.336.75.75.75h1.483a6.5 6.5 0 0 0 1.079 1.5H10.25A2.25 2.25 0 0 1 8 19.75V16H4.25A2.25 2.25 0 0 1 2 13.75v-3.5A2.25 2.25 0 0 1 4.25 8H8V4.25A2.25 2.25 0 0 1 10.25 2zm3.75 11.999a.5.5 0 0 0-.5.5V17h-2.505a.5.5 0 0 0 0 1h2.506v2.504a.5.5 0 0 0 1 0V18h2.496a.5.5 0 0 0 0-1H18v-2.501a.5.5 0 0 0-.5-.5M4.25 9.5a.75.75 0 0 0-.75.75v3.5c0 .414.336.75.75.75H8v-5zm6-6a.75.75 0 0 0-.75.75V8h5V4.25a.75.75 0 0 0-.75-.75z");
}

</style>
