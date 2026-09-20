<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xryy_f6rn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:stat-3" /></template>
<style>
.xryy_f6rn {
  fill: currentColor;
  d: path("m7.4 21.375l-1.4-1.4l6-6l6 6l-1.4 1.4L12 16.8zm0-6l-1.4-1.4l6-6l6 6l-1.4 1.4L12 10.8zm0-6L6 7.975l6-6l6 6l-1.4 1.4L12 4.8z");
}

</style>
