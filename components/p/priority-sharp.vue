<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i86rfzbkj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:priority-sharp" /></template>
<style>
.i86rfzbkj {
  fill: currentColor;
  d: path("M9 21q-2.5 0-4.25-1.75T3 15V9q0-2.5 1.75-4.25T9 3h6q2.5 0 4.25 1.75T21 9v6q0 2.5-1.75 4.25T15 21zm2-5l6-6l-1.4-1.4l-4.6 4.6L8.8 11l-1.4 1.4z");
}

</style>
