<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t7mnajbxg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:work-iq-24-regular" /></template>
<style>
.t7mnajbxg {
  fill: currentColor;
  d: path("M12 3c5.523 0 10 4.477 10 10a6.5 6.5 0 0 1-3.5 5.766V19a2.5 2.5 0 0 0 2.5 2.5h.25a.75.75 0 0 1 0 1.5H21a4 4 0 0 1-3.986-3.68c-.486.116-.993.18-1.514.18h-1a4 4 0 1 1 4-4v1.499a4.99 4.99 0 0 0 2-3.999a8.5 8.5 0 0 0-17 0v.5a3 3 0 0 0 3 3h1.75a.75.75 0 0 1 0 1.5H6.5A4.5 4.5 0 0 1 2 13.5V13C2 7.477 6.477 3 12 3m2.5 10a2.5 2.5 0 0 0 0 5h1c.523 0 1.026-.08 1.5-.23V15.5a2.5 2.5 0 0 0-2.5-2.5");
}

</style>
