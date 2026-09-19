<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e9pln-36v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-7k-plus" /></template>
<style>
.e9pln-36v {
  fill: currentColor;
  d: path("M21 3H3v18h18zM8.5 15H6.75l1.38-4.5H5.5V9h4.86zm7.5 0h-1.75l-1.75-2.25V15H11V9h1.5v2.25L14.25 9H16l-2.25 3zm3-2.5h-1.5V14h-1v-1.5H15v-1h1.5V10h1v1.5H19z");
}

</style>
