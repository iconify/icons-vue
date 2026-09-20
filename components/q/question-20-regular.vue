<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="s_483cbbk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:question-20-regular" /></template>
<style>
.s_483cbbk {
  fill: currentColor;
  d: path("M10 3C7.794 3 6 4.794 6 7a.5.5 0 0 0 1 0c0-1.654 1.346-3 3-3s3 1.346 3 3c0 1.249-.692 1.863-1.575 2.62l-.032.027C10.534 10.384 9.5 11.27 9.5 13v.5a.5.5 0 0 0 1 0V13c0-1.249.692-1.863 1.575-2.62l.032-.027C12.967 9.615 14 8.731 14 7c0-2.206-1.794-4-4-4m0 14a.75.75 0 1 0 0-1.5a.75.75 0 0 0 0 1.5");
}

</style>
