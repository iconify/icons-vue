<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rn8ol4b-j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-hexagon" /></template>
<style>
.rn8ol4b-j {
  fill: currentColor;
  d: path("M17.2 3H6.8l-5.2 9l5.2 9h10.4l5.2-9z");
}

</style>
