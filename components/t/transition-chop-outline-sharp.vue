<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kxcaocbcl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:transition-chop-outline-sharp" /></template>
<style>
.kxcaocbcl {
  fill: currentColor;
  d: path("M2 20V4h20v16zm2-3.45l11.55-3L13.6 6H4zM6.375 18H20V6h-4.325L18 15zM4 6");
}

</style>
