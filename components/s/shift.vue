<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ykmzjjlqy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:shift" /></template>
<style>
.ykmzjjlqy {
  fill: currentColor;
  d: path("M8 21v-8H3l9-11l9 11h-5v8z");
}

</style>
