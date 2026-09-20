<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="szqze4biz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:virtual-network-20-regular" /></template>
<style>
.szqze4biz {
  fill: currentColor;
  d: path("M4.825 6.12a.5.5 0 0 1 .055.705L2.159 10l2.72 3.175a.5.5 0 1 1-.759.65l-3-3.5a.5.5 0 0 1 0-.65l3-3.5a.5.5 0 0 1 .705-.055m10.295 7.055a.5.5 0 0 0 .76.65l3-3.5a.5.5 0 0 0 0-.65l-3-3.5a.5.5 0 1 0-.76.65L17.842 10zM6 11a1 1 0 1 0 0-2a1 1 0 0 0 0 2m5-1a1 1 0 1 1-2 0a1 1 0 0 1 2 0m3 1a1 1 0 1 0 0-2a1 1 0 0 0 0 2");
}

</style>
