<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<path class="sk1msob9y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:resize-28-regular" /></template>
<style>
.sk1msob9y {
  fill: currentColor;
  d: path("M11.75 3h-5A3.75 3.75 0 0 0 3 6.75v2a.75.75 0 0 0 1.5 0v-2A2.25 2.25 0 0 1 6.75 4.5h5a.75.75 0 0 0 0-1.5m-5 20.5a2.25 2.25 0 0 1-2.25-2.25v-6.5a2.25 2.25 0 0 1 2.25-2.25h6.5a2.25 2.25 0 0 1 2.25 2.25v6.5a2.25 2.25 0 0 1-2.25 2.25zM3 21.25A3.75 3.75 0 0 0 6.75 25h6.5A3.75 3.75 0 0 0 17 21.25v-6.5A3.75 3.75 0 0 0 13.25 11h-6.5A3.75 3.75 0 0 0 3 14.75zM19.25 25a.75.75 0 0 1 0-1.5h2a2.25 2.25 0 0 0 2.25-2.25v-5a.75.75 0 0 1 1.5 0v5A3.75 3.75 0 0 1 21.25 25zM25 11.75a.75.75 0 0 1-1.5 0v-5a2.25 2.25 0 0 0-2.25-2.25h-5a.75.75 0 0 1 0-1.5h5A3.75 3.75 0 0 1 25 6.75z");
}

</style>
