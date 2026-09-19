<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lxp3ut8mc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-score" /></template>
<style>
.lxp3ut8mc {
  fill: currentColor;
  d: path("M21 3H3v18h18zm-9 2h1.5v3l2-3h1.7l-2 3l2 3h-1.7l-2-3v3H12zM7 7.25h2.5V6.5H7V5h4v3.75H8.5v.75H11V11H7zM19 13l-6 6l-4-4l-4 4v-2.5l4-4l4 4l6-6z");
}

</style>
