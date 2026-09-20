<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ux106quse"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:stat-1-outline-sharp" /></template>
<style>
.ux106quse {
  fill: currentColor;
  d: path("m7.4 15.375l-1.4-1.4l6-6l6 6l-1.4 1.4L12 10.8z");
}

</style>
