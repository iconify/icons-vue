<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="majqvxbny"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:phone-chat-16-filled" /></template>
<style>
.majqvxbny {
  fill: currentColor;
  d: path("M4 2.75C4 1.784 4.784 1 5.75 1h4.5c.966 0 1.75.784 1.75 1.75v3.272a5.5 5.5 0 0 0-5.51 7.75L6.117 15H5.75A1.75 1.75 0 0 1 4 13.25zM11.5 16a4.5 4.5 0 1 0-3.936-2.318l-.545 1.789a.41.41 0 0 0 .51.51l1.79-.544A4.5 4.5 0 0 0 11.5 16M9 10.5a.5.5 0 0 1 .5-.5h4a.5.5 0 0 1 0 1h-4a.5.5 0 0 1-.5-.5m.5 2.5a.5.5 0 0 1 0-1h2a.5.5 0 0 1 0 1z");
}

</style>
