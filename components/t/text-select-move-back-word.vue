<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="osqejdbzg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:text-select-move-back-word" /></template>
<style>
.osqejdbzg {
  fill: currentColor;
  d: path("m7 16l-4-4l4-4l1.4 1.4L6.825 11H13v2H6.825L8.4 14.6zm8 5V3h6v18zM11 5V3h2v2zm0 16v-2h2v2zM7 5V3h2v2zm0 16v-2h2v2zM3 5V3h2v2zm0 16v-2h2v2z");
}

</style>
