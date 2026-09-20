<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c9r0ne_hc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:pause-rounded" /></template>
<style>
.c9r0ne_hc {
  fill: currentColor;
  d: path("M15 18q-.402 0-.701-.299T14 17V7q0-.402.299-.701T15 6h1.5q.402 0 .701.299T17.5 7v10q0 .402-.299.701T16.5 18zm-7.5 0q-.402 0-.701-.299T6.5 17V7q0-.402.299-.701T7.5 6H9q.402 0 .701.299T10 7v10q0 .402-.299.701T9 18z");
}

</style>
