<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pgirorbed"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:pulse-square-24-regular" /></template>
<style>
.pgirorbed {
  fill: currentColor;
  d: path("M17.75 3A3.25 3.25 0 0 1 21 6.25v11.5A3.25 3.25 0 0 1 17.75 21H6.25A3.25 3.25 0 0 1 3 17.75V6.25A3.25 3.25 0 0 1 6.25 3zM6.25 4.5A1.75 1.75 0 0 0 4.5 6.25v11.5c0 .966.784 1.75 1.75 1.75h11.5a1.75 1.75 0 0 0 1.75-1.75V6.25a1.75 1.75 0 0 0-1.75-1.75zm3.563 3.448a.75.75 0 0 1 1.332-.08l.05.103l2.382 5.946l1.003-2.004a.75.75 0 0 1 .566-.406l.105-.008h2a.75.75 0 0 1 .101 1.493l-.101.007h-1.537L14.17 16.08a.75.75 0 0 1-1.319.043l-.047-.1l-2.337-5.834l-1.035 2.362a.75.75 0 0 1-.578.44L8.746 13H6.751a.75.75 0 0 1-.103-1.493l.103-.007h1.505z");
}

</style>
