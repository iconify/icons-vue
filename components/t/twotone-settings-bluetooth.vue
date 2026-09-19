<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p8eikcb_e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-settings-bluetooth" /></template>
<style>
.p8eikcb_e {
  fill: currentColor;
  d: path("M11 24h2v-2h-2zm-4 0h2v-2H7zm8 0h2v-2h-2zm2.71-18.29L12 0h-1v7.59L6.41 3L5 4.41L10.59 10L5 15.59L6.41 17L11 12.41V20h1l5.71-5.71l-4.3-4.29zM13 3.83l1.88 1.88L13 7.59zm1.88 10.46L13 16.17v-3.76z");
}

</style>
