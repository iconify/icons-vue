<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h_b18wd6d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:priority" /></template>
<style>
.h_b18wd6d {
  fill: currentColor;
  d: path("M9 20q-2.083 0-3.542-1.458Q4 17.083 4 15V9q0-2.083 1.458-3.542Q6.917 4 9 4h6q2.083 0 3.542 1.458Q20 6.917 20 9v6q0 2.083-1.458 3.542Q17.083 20 15 20zm2-4.692L16.308 10l-.708-.708l-4.6 4.6l-2.2-2.2l-.708.708z");
}

</style>
