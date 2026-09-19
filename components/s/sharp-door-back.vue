<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jiu1upb9y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-door-back" /></template>
<style>
.jiu1upb9y {
  fill: currentColor;
  d: path("M19 19V3H5v16H3v2h18v-2zm-8-6H9v-2h2z");
}

</style>
