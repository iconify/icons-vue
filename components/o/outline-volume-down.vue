<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zfjcyuc-v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:outline-volume-down" /></template>
<style>
.zfjcyuc-v {
  fill: currentColor;
  d: path("M16 7.97v8.05c1.48-.73 2.5-2.25 2.5-4.02A4.5 4.5 0 0 0 16 7.97M5 9v6h4l5 5V4L9 9zm7-.17v6.34L9.83 13H7v-2h2.83z");
}

</style>
