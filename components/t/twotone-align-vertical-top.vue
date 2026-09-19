<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vi47-hbwa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-align-vertical-top" /></template>
<style>
.vi47-hbwa {
  fill: currentColor;
  d: path("M22 2v2H2V2zM7 22h3V6H7zm7-6h3V6h-3z");
}

</style>
