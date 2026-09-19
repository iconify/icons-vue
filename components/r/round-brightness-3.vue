<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qcu_yop9j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:round-brightness-3" /></template>
<style>
.qcu_yop9j {
  fill: currentColor;
  d: path("M8.93 2h-.14c-.83.02-1.09 1.12-.39 1.56A10 10 0 0 1 13.03 12c0 3.55-1.84 6.66-4.62 8.43c-.71.46-.43 1.55.41 1.57h.21c6.05 0 10.86-5.39 9.87-11.63c-.76-4.84-5.07-8.42-9.97-8.37");
}

</style>
