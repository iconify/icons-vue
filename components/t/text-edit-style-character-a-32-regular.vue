<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="w6e01ib5r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:text-edit-style-character-a-32-regular" /></template>
<style>
.w6e01ib5r {
  fill: currentColor;
  d: path("M10.421 2.61a1 1 0 0 0-1.842 0l-5.5 13a1 1 0 1 0 1.842.78L6.355 13h6.29l1.434 3.39l.002.004l1.526-1.526zm-.92 2.956L11.798 11H7.201zm18.173 5.762a4.536 4.536 0 0 0-6.414 0l-9.42 9.42a4 4 0 0 0-1.018 1.73l-1.785 6.25a1 1 0 0 0 1.236 1.237l6.254-1.787a4 4 0 0 0 1.73-1.018l9.417-9.417a4.536 4.536 0 0 0 0-6.415m-5 1.415a2.536 2.536 0 0 1 3.586 3.585l-9.418 9.418c-.24.24-.538.416-.865.509l-4.523 1.292l1.292-4.52a2 2 0 0 1 .508-.865z");
}

</style>
