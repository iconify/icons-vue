<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yxkfhs9ju"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:outline-h-mobiledata" /></template>
<style>
.yxkfhs9ju {
  fill: currentColor;
  d: path("M15 11H9V7H7v10h2v-4h6v4h2V7h-2z");
}

</style>
