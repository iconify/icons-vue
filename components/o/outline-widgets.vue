<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eh__dfjjj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:outline-widgets" /></template>
<style>
.eh__dfjjj {
  fill: currentColor;
  d: path("m16.66 4.52l2.83 2.83l-2.83 2.83l-2.83-2.83zM9 5v4H5V5zm10 10v4h-4v-4zM9 15v4H5v-4zm7.66-13.31L11 7.34L16.66 13l5.66-5.66zM11 3H3v8h8zm10 10h-8v8h8zm-10 0H3v8h8z");
}

</style>
