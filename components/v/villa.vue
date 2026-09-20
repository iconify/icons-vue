<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hg9ku-7_y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:villa" /></template>
<style>
.hg9ku-7_y {
  fill: currentColor;
  d: path("M10 20v-6.992h6.923q0-.64.452-1.093q.451-.453 1.085-.453t1.087.452T20 13v7h-4.23v-3.308h-1.54V20zm-6 0V8.692l11.23-4.326V12H9v8z");
}

</style>
