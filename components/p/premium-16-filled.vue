<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="u2ya-k61d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:premium-16-filled" /></template>
<style>
.u2ya-k61d {
  fill: currentColor;
  d: path("M3.75 2a.75.75 0 0 0-.662.397l-2 3.75a.75.75 0 0 0 .071.815l6.25 8a.75.75 0 0 0 1.182 0l6.25-8a.75.75 0 0 0 .07-.815l-2-3.75A.75.75 0 0 0 12.25 2zm-.883 4L4.2 3.5h1.277L4.852 6zm.616 1.5h1.544l1.029 3.293zm3.115 0h2.804L8 11.986zm4.375 0h1.544l-2.573 3.293zm2.16-1.5h-1.985l-.625-2.5H11.8zM9.602 6H6.398l.625-2.5h1.954z");
}

</style>
