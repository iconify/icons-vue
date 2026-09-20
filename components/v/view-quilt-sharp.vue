<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xckjz4b9z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:view-quilt-sharp" /></template>
<style>
.xckjz4b9z {
  fill: currentColor;
  d: path("M9.594 11.616V6H20v5.616zM15.175 18v-5.615H20V18zm-5.58 0v-5.615h4.81V18zM4 18V6h4.825v12z");
}

</style>
