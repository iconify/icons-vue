<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="xm19uacjr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:table-simple-checkmark-20-filled" /></template>
<style>
.xm19uacjr {
  fill: currentColor;
  d: path("M14 17h-3.5v-6.5H17V14a3 3 0 0 1-3 3m3-7.5h-6.5V3H14a3 3 0 0 1 3 3zm-7.5 0V3H6a3 3 0 0 0-3 3v3.5zm0 7.5v-6.5H3V14a3 3 0 0 0 3 3zm5.852-3.896a.5.5 0 0 0-.707-.708l-1.397 1.397l-.399-.397a.5.5 0 0 0-.706.708l.753.75a.5.5 0 0 0 .706 0z");
}

</style>
