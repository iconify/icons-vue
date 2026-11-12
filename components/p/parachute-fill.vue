<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zjpmspbke"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:parachute-fill" /></template>
<style>
.zjpmspbke {
  fill: currentColor;
  d: path("M21.707 9.707L13 18.414V20h2a1 1 0 0 1 0 2H9a1 1 0 0 1 0-2h2v-1.586L2.293 9.707A1 1 0 0 1 2 9v-.001c0-1.104.275-2.193.847-3.141c.553-.914 1.348-1.652 2.254-2.21C7.12 2.406 9.662 2 12 2s4.88.406 6.899 1.648c.906.558 1.701 1.296 2.254 2.21C21.725 6.806 22 7.895 22 9c0 .265-.105.52-.293.707M11 15.586V9.551C8.909 8.31 6.816 8.138 4.626 9.212Zm2 0l6.374-6.374c-2.19-1.074-4.283-.902-6.374.339Z");
}

</style>
