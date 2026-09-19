<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g6jk1obxb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-swipe-right" /></template>
<style>
.g6jk1obxb {
  fill: currentColor;
  d: path("M20.18 15.4L19.1 23h-9L5 17.62l1.22-1.23l3.78.85V6.5c0-.83.67-1.5 1.5-1.5s1.5.67 1.5 1.5v6h1.38zm-.27-9.9H17V7h5V2h-1.5v2.02A13.4 13.4 0 0 0 12 1C6.51 1 2.73 4.12 2 7h1.57C4.33 5.02 7.26 2.5 12 2.5c3.03 0 5.79 1.14 7.91 3");
}

</style>
