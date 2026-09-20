<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b7axvgf-n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:pages-sharp" /></template>
<style>
.b7axvgf-n {
  fill: currentColor;
  d: path("M4 20V4h16v16zm5.517-4.442L12 14.052l2.483 1.506l-.66-2.825l2.196-1.885l-2.886-.256L12 7.942l-1.133 2.65l-2.886.256l2.196 1.885z");
}

</style>
