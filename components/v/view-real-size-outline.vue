<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yk1uh2y2z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:view-real-size-outline" /></template>
<style>
.yk1uh2y2z {
  fill: currentColor;
  d: path("M7 17V9H5V7h4v10zm4 0v-2h2v2zm5 0V9h-2V7h4v10zm-5-4v-2h2v2z");
}

</style>
