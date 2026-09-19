<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g0r1g8t_h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:outline-hexagon" /></template>
<style>
.g0r1g8t_h {
  fill: currentColor;
  d: path("M17.2 3H6.8l-5.2 9l5.2 9h10.4l5.2-9zm-1.15 16h-8.1l-4.04-7l4.04-7h8.09l4.04 7z");
}

</style>
