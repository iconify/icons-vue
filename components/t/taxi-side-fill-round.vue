<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xinm774ix"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:taxi-side-fill-round" /></template>
<style>
.xinm774ix {
  fill: currentColor;
  d: path("M12 3a1 1 0 0 1 0 2H9a1 1 0 0 1 0-2ZM6.293 7.293C7.252 6.335 8.683 6 10 6h1c1.317 0 2.748.335 3.707 1.293L18.414 11H19a3 3 0 0 1 3 3v2c0 1.32-.866 2.487-2.128 2.872a3 3 0 0 1-5.701.128H9.829a3 3 0 0 1-5.7-.128A3.005 3.005 0 0 1 2 16v-4c0-.265.105-.52.293-.707ZM9 8.073Q9.325 8 9.657 8H9Zm-1.462.803L4 12.414V13h5V8.073a3 3 0 0 0-1.462.803M11 13h6.586l-.291-.291l-.002-.002l-3.829-3.828l-.002-.003A3 3 0 0 0 11.343 8H11Zm-4.709 5.705l.002.002l.002.002a1 1 0 0 0 1.41 0l.002-.002l.002-.002a1 1 0 0 0 0-1.41l-.002-.002l-.002-.002a1 1 0 0 0-1.41 0l-.002.002l-.002.002a1 1 0 0 0 0 1.41m11.414.004l.002-.002l.002-.002a1 1 0 0 0 0-1.41l-.002-.002l-.002-.002a1 1 0 0 0-1.41 0l-.002.002l-.002.002a1 1 0 0 0 1.414 1.414");
}

</style>
