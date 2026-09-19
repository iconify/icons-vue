<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dnbz8tbng"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-phone-iphone" /></template>
<style>
.dnbz8tbng {
  fill: currentColor;
  d: path("M18 1H5v22h13zm-6.5 21c-.83 0-1.5-.67-1.5-1.5s.67-1.5 1.5-1.5s1.5.67 1.5 1.5s-.67 1.5-1.5 1.5m4.5-4H7V4h9z");
}

</style>
