<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="qq59n608s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:question-32-regular" /></template>
<style>
.qq59n608s {
  fill: currentColor;
  d: path("M11 11a5 5 0 0 1 10 0c0 1.456-.33 2.31-.757 2.92c-.414.592-.95 1.013-1.637 1.555l-.227.178c-.767.608-1.648 1.348-2.311 2.518C15.4 19.348 15 20.872 15 23a1 1 0 1 0 2 0c0-1.872.35-3.036.807-3.843c.462-.814 1.08-1.355 1.814-1.936l.23-.181c.66-.516 1.436-1.124 2.031-1.975c.699-1 1.118-2.27 1.118-4.065a7 7 0 1 0-14 0a1 1 0 1 0 2 0m5 17.75a1.25 1.25 0 1 0 0-2.5a1.25 1.25 0 0 0 0 2.5");
}

</style>
