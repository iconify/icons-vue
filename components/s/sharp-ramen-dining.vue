<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zpty5cbia"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-ramen-dining" /></template>
<style>
.zpty5cbia {
  fill: currentColor;
  d: path("M22 3.51V2L4 3.99V12H2c0 3.69 2.47 6.86 6 8.25V22h8v-1.75c3.53-1.39 6-4.56 6-8.25H10.5V8H22V6.5H10.5V4.78zM6.5 5.22V6.5h-1V5.34zM5.5 8h1v4h-1zM9 12H8V8h1zm0-5.5H8V5.06l1-.11z");
}

</style>
