<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wzan7becx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-no-encryption-gmailerrorred" /></template>
<style>
.wzan7becx {
  fill: currentColor;
  d: path("M8.9 6c0-1.71 1.39-3.1 3.1-3.1s3.1 1.39 3.1 3.1v2h-4.66L20 17.56V8h-3V6.22c0-2.61-1.91-4.94-4.51-5.19c-2.53-.25-4.72 1.41-5.32 3.7L8.9 6.46zM4.41 4.81L3 6.22L4.78 8H4v14h14.78l1 1l1.41-1.41z");
}

</style>
