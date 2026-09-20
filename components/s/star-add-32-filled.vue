<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="r7jkl914a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:star-add-32-filled" /></template>
<style>
.r7jkl914a {
  fill: currentColor;
  d: path("M22.5 15a7.5 7.5 0 1 1 0 15a7.5 7.5 0 0 1 0-15M14.654 3.839c.549-1.119 2.144-1.119 2.693 0l3.2 6.521l7.17 1.05c1.228.179 1.719 1.685.833 2.554l-1.064 1.044A9 9 0 0 0 14.009 25.49l-4.407 2.332c-1.1.582-2.389-.351-2.18-1.578l1.224-7.183l-5.196-5.097c-.884-.869-.392-2.375.834-2.555l7.171-1.049zm8.096 13.16a.75.75 0 0 0-.75.75v3.75h-3.75a.75.75 0 0 0 0 1.5H22v3.75a.75.75 0 0 0 1.5 0V23h3.75a.75.75 0 0 0 0-1.5H23.5v-3.75a.75.75 0 0 0-.75-.75");
}

</style>
