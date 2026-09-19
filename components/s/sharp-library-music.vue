<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j7zv5bczn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-library-music" /></template>
<style>
.j7zv5bczn {
  fill: currentColor;
  d: path("M22 2H6v16h16zm-4 5h-3v5.5a2.5 2.5 0 0 1-5 0a2.5 2.5 0 0 1 2.5-2.5c.57 0 1.08.19 1.5.51V5h4zM4 6H2v16h16v-2H4z");
}

</style>
