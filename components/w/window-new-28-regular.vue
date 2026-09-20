<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<path class="gb1277k9l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:window-new-28-regular" /></template>
<style>
.gb1277k9l {
  fill: currentColor;
  d: path("M21.25 3A3.75 3.75 0 0 1 25 6.75v11.5a3.75 3.75 0 0 1-3.064 3.686A3.75 3.75 0 0 1 18.25 25h-9A6.25 6.25 0 0 1 3 18.75v-9a3.75 3.75 0 0 1 3.063-3.687A3.75 3.75 0 0 1 9.75 3zM6 7.63a2.25 2.25 0 0 0-1.5 2.12v9a4.75 4.75 0 0 0 4.75 4.75h9c.98 0 1.81-.627 2.12-1.5H9.75A3.75 3.75 0 0 1 6 18.25zM9.75 4.5A2.25 2.25 0 0 0 7.5 6.75v11.5a2.25 2.25 0 0 0 2.25 2.25h11.5a2.25 2.25 0 0 0 2.25-2.25V6.75a2.25 2.25 0 0 0-2.25-2.25zm9.5 3.5a.75.75 0 0 1 .75.75v6a.75.75 0 0 1-1.5 0v-4.19l-6.22 6.22a.75.75 0 1 1-1.06-1.06l6.22-6.22h-4.19a.75.75 0 0 1 0-1.5z");
}

</style>
