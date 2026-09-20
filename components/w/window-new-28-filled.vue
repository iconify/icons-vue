<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<path class="w-m1rk56w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:window-new-28-filled" /></template>
<style>
.w-m1rk56w {
  fill: currentColor;
  d: path("M21.25 3A3.75 3.75 0 0 1 25 6.75v11.5a3.75 3.75 0 0 1-3.064 3.686A3.75 3.75 0 0 1 18.25 25h-9A6.25 6.25 0 0 1 3 18.75v-9a3.75 3.75 0 0 1 3.063-3.687A3.75 3.75 0 0 1 9.75 3zM6 7.63a2.25 2.25 0 0 0-1.5 2.12v9a4.75 4.75 0 0 0 4.75 4.75h9c.98 0 1.81-.627 2.12-1.5H9.75A3.75 3.75 0 0 1 6 18.25zm7.25.37a.75.75 0 0 0 0 1.5h4.19l-6.22 6.22a.75.75 0 1 0 1.06 1.06l6.22-6.22v4.19a.75.75 0 0 0 1.5 0v-6a.75.75 0 0 0-.75-.75z");
}

</style>
