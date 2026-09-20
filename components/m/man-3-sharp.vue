<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rmmzo6boe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:man-3-sharp" /></template>
<style>
.rmmzo6boe {
  fill: currentColor;
  d: path("M10.23 21.75v-6.57H8.463V7.674h7.077v7.5h-1.77v6.577zM12 6.308l-1.942-1.942L12 2.423l1.942 1.943z");
}

</style>
