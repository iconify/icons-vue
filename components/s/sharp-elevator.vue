<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hi4059bab"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-elevator" /></template>
<style>
.hi4059bab {
  fill: currentColor;
  d: path("M21 3H3v18h18zM8.5 6a1.25 1.25 0 1 1 0 2.5a1.25 1.25 0 0 1 0-2.5m2.5 8h-1v4H7v-4H6V9.5h5zm4.5 3L13 13h5zM13 11l2.5-4l2.5 4z");
}

</style>
