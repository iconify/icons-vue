<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="isujp2byr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:text-direction-rotate-90-ltr-20-regular" /></template>
<style>
.isujp2byr {
  fill: currentColor;
  d: path("M17 6.5a.5.5 0 0 0-.324-.468l-8-3a.5.5 0 1 0-.351.936L11 4.972v3.057L8.325 9.032a.5.5 0 0 0 .35.936l8-3A.5.5 0 0 0 17 6.5m-1.924 0L12 7.654V5.347zM5 3.5a.5.5 0 0 1 1 0v11.793l1.146-1.147a.5.5 0 1 1 .708.707l-2 2a.5.5 0 0 1-.351.147h-.006a.5.5 0 0 1-.35-.146l-2-2a.5.5 0 1 1 .707-.708L5 15.293zm8 7a.5.5 0 0 1 1 0v4.793l1.146-1.147a.5.5 0 0 1 .708.707l-2 2a.5.5 0 0 1-.708 0l-2-2a.5.5 0 0 1 .708-.707L13 15.293z");
}

</style>
