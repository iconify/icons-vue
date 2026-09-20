<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j-00tc0nb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:score-sharp" /></template>
<style>
.j-00tc0nb {
  fill: currentColor;
  d: path("M3 21V3h18v18zm9-9h1.5V6H12zm3.5 0h1.7l-2-3l2-3h-1.7l-2 3zM7 12h4v-1.5H8.5v-.75H11V6H7v1.5h2.5v.75H7zm12 1v-2.5l-6 6l-4-4l-4 4V19l4-4l4 4z");
}

</style>
