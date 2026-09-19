<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="szjrfxbam"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-1k-plus" /></template>
<style>
.szjrfxbam {
  fill: currentColor;
  d: path("M21 3H3v18h18zM9 15H7.5v-4.5H6V9h3zm4.75 0L12 12.75V15h-1.5V9H12v2.25L13.75 9h1.75l-2.25 3l2.25 3zM19 12.5h-1.5V14h-1v-1.5H15v-1h1.5V10h1v1.5H19z");
}

</style>
