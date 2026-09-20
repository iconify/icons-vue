<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w5873umpg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:unfold-less" /></template>
<style>
.w5873umpg {
  fill: currentColor;
  d: path("m8.9 19.308l-.708-.708L12 14.792l3.808 3.808l-.708.708l-3.1-3.1zm3.1-10.1L8.192 5.4l.708-.708l3.1 3.1l3.1-3.1l.708.708z");
}

</style>
