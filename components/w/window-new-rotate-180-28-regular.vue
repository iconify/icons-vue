<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<path class="a_yd6zlxq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:window-new-rotate-180-28-regular" /></template>
<style>
.a_yd6zlxq {
  fill: currentColor;
  d: path("M6.75 25A3.75 3.75 0 0 1 3 21.25V9.75a3.75 3.75 0 0 1 3.064-3.686A3.75 3.75 0 0 1 9.75 3h9A6.25 6.25 0 0 1 25 9.25v9a3.75 3.75 0 0 1-3.064 3.686A3.75 3.75 0 0 1 18.25 25zM22 20.37a2.25 2.25 0 0 0 1.5-2.12v-9a4.75 4.75 0 0 0-4.75-4.75h-9c-.98 0-1.81.627-2.12 1.5h10.62A3.75 3.75 0 0 1 22 9.75zm-3.75 3.13a2.25 2.25 0 0 0 2.25-2.25V9.75a2.25 2.25 0 0 0-2.25-2.25H6.75A2.25 2.25 0 0 0 4.5 9.75v11.5a2.25 2.25 0 0 0 2.25 2.25zM8.75 20a.75.75 0 0 1-.75-.75v-6a.75.75 0 0 1 1.5 0v4.19l6.22-6.22a.75.75 0 1 1 1.06 1.06l-6.22 6.22h4.19a.75.75 0 0 1 0 1.5z");
}

</style>
