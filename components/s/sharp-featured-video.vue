<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="celeutb3k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-featured-video" /></template>
<style>
.celeutb3k {
  fill: currentColor;
  d: path("M23 3H1v18h22zm-11 9H3V5h9z");
}

</style>
