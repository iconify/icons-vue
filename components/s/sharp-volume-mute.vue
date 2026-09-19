<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xs8_ejdrv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-volume-mute" /></template>
<style>
.xs8_ejdrv {
  fill: currentColor;
  d: path("M7 9v6h4l5 5V4l-5 5z");
}

</style>
