<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="to_np0b3g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:round-bluetooth" /></template>
<style>
.to_np0b3g {
  fill: currentColor;
  d: path("m17 7l-4.29-4.29c-.63-.63-1.71-.19-1.71.7v6.18L7.11 5.7A.996.996 0 1 0 5.7 7.11L10.59 12L5.7 16.89a.996.996 0 1 0 1.41 1.41L11 14.41v6.18c0 .89 1.08 1.34 1.71.71L17 17a.996.996 0 0 0 0-1.41L13.41 12L17 8.42c.39-.39.39-1.03 0-1.42m-4-1.17l1.88 1.88L13 9.59zm1.88 10.46L13 18.17v-3.76z");
}

</style>
