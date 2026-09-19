<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pc1i52siu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-1k" /></template>
<style>
.pc1i52siu {
  fill: currentColor;
  d: path("M21 3H3v18h18zM10 15H8.5v-4.5H7V9h3zm7 0h-1.75l-1.75-2.25V15H12V9h1.5v2.25L15.25 9H17l-2.25 3z");
}

</style>
