<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vg99qjfex"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:weight-fill" /></template>
<style>
.vg99qjfex {
  fill: currentColor;
  d: path("M14.829 7H15c.732 0 1.416.341 1.927.852c.523.523.865 1.192 1.043 1.905l2 8c.253 1.014.015 2.242-.87 2.883c-.321.233-.703.36-1.1.36H6c-.397 0-.779-.127-1.1-.36c-.885-.641-1.123-1.869-.87-2.883l2-8c.178-.713.52-1.382 1.043-1.905C7.584 7.341 8.268 7 9 7h.171a3 3 0 1 1 5.658 0m-3.536-1.707a.999.999 0 1 0 1.414 1.414a.999.999 0 1 0-1.414-1.414");
}

</style>
