<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="td2kkx1ph"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-switch-left" /></template>
<style>
.td2kkx1ph {
  fill: currentColor;
  d: path("M8.5 8.62v6.76L5.12 12zM10 5l-7 7l7 7zm4 0v14l7-7z");
}

</style>
