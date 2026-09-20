<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dsvwdvbmx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:voice-chat-off-sharp" /></template>
<style>
.dsvwdvbmx {
  fill: currentColor;
  d: path("M16.5 11H18V9h-1.5zM14 7v4.15L12.75 9.9V5h-1.5v3.4L4.85 2H22v16h-1.15l-5.35-5.35V7zm6.5 16.3L15.15 18H6l-4 4V4.8L.7 3.5l1.4-1.4l19.8 19.8zM12.2 15l-.95-.95V15zm-3.7-2H10v-.2l-1.5-1.5zM6 11h1.5v-.7L6.2 9H6z");
}

</style>
