<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gkmrd3b5u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:outline-hourglass-bottom" /></template>
<style>
.gkmrd3b5u {
  fill: currentColor;
  d: path("m18 22l-.01-6L14 12l3.99-4.01L18 2H6v6l4 4l-4 3.99V22zM8 7.5V4h8v3.5l-4 4z");
}

</style>
