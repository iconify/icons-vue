<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<path class="qvmqlxbqe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:star-three-quarter-28-filled" /></template>
<style>
.qvmqlxbqe {
  fill: currentColor;
  d: path("m17 7.349l-1.698-3.441c-.532-1.078-2.069-1.078-2.6 0L10.01 9.36l-6.017.875c-1.19.173-1.664 1.634-.804 2.473l4.355 4.244l-1.028 5.993c-.203 1.185 1.04 2.088 2.104 1.529l5.382-2.83L17 23.221z");
}

</style>
