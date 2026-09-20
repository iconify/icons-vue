<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="mmd2itbjp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:text-line-spacing-20-filled" /></template>
<style>
.mmd2itbjp {
  fill: currentColor;
  d: path("M15.25 11a.75.75 0 0 1 .75.75v3.69l.72-.72a.75.75 0 1 1 1.06 1.06l-2 2a.75.75 0 0 1-1.06 0l-2-2a.75.75 0 0 1 1.06-1.06l.72.72v-3.69a.75.75 0 0 1 .75-.75m-7 3a.75.75 0 0 1 0 1.5h-5.5a.75.75 0 0 1 0-1.5zm3-5a.75.75 0 0 1 0 1.5h-8.5a.75.75 0 0 1 0-1.5zm3.47-6.78a.75.75 0 0 1 1.06 0l2 2a.75.75 0 1 1-1.06 1.06L16 4.56v3.69a.75.75 0 0 1-1.5 0V4.56l-.72.72a.75.75 0 0 1-1.06-1.06zM8.25 4a.75.75 0 1 1 0 1.5h-5.5a.75.75 0 0 1 0-1.5z");
}

</style>
