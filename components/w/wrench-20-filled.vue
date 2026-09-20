<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="eqh2jdbev"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:wrench-20-filled" /></template>
<style>
.eqh2jdbev {
  fill: currentColor;
  d: path("M13.5 2a4.5 4.5 0 0 0-4.417 5.36l-6.426 6.658a2.357 2.357 0 0 0 3.374 3.293l6.365-6.448Q12.929 11 13.5 11a4.5 4.5 0 0 0 4.386-5.51a.5.5 0 0 0-.84-.242L14.5 7.793L12.208 5.5l2.545-2.545a.5.5 0 0 0-.242-.84A4.5 4.5 0 0 0 13.501 2");
}

</style>
