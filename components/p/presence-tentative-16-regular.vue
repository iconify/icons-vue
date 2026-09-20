<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="pbfc94bso"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:presence-tentative-16-regular" /></template>
<style>
.pbfc94bso {
  fill: currentColor;
  d: path("M15.993 8.097A8 8 0 0 1 8.091 16zm-.456-2.768a8 8 0 0 0-1.135-2.118L3.206 14.409a8 8 0 0 0 2.118 1.134zM1.591 12.798a8 8 0 0 1-1.138-2.119L10.673.46c.767.273 1.48.66 2.118 1.139zM7.908 0A8 8 0 0 0-.006 7.914z");
}

</style>
