<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zz26l_w5o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:warning-lock-open-24-regular" /></template>
<style>
.zz26l_w5o {
  fill: currentColor;
  d: path("M21.5 11.5A2.5 2.5 0 0 1 24 14a.75.75 0 0 1-1.5 0a1 1 0 1 0-2 0v1h1a1.5 1.5 0 0 1 1.5 1.5v5a1.5 1.5 0 0 1-1.5 1.5h-6a1.5 1.5 0 0 1-1.5-1.5v-5a1.5 1.5 0 0 1 1.5-1.5H19v-1a2.5 2.5 0 0 1 2.5-2.5M9.138 3.708c1.228-2.276 4.494-2.276 5.721 0l4.2 7.785a3.5 3.5 0 0 0-.906 1.483L13.54 4.42c-.661-1.225-2.42-1.225-3.081 0L3.715 16.922a1.75 1.75 0 0 0 1.54 2.581H13v1.5H5.255c-2.46 0-4.028-2.628-2.86-4.793zM18.5 18a1 1 0 1 0 0 2a1 1 0 0 0 0-2M12 15.001a1 1 0 1 1-.002 2.001a1 1 0 0 1 .002-2m0-7.5a.75.75 0 0 1 .75.75v4.5a.751.751 0 0 1-1.5 0v-4.5a.75.75 0 0 1 .75-.75");
}

</style>
