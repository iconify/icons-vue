<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g1p2f0aun"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-newspaper" /></template>
<style>
.g1p2f0aun {
  fill: currentColor;
  d: path("m22 3l-1.67 1.67L18.67 3L17 4.67L15.33 3l-1.66 1.67L12 3l-1.67 1.67L8.67 3L7 4.67L5.33 3L3.67 4.67L2 3v18h20zM11 19H4v-6h7zm9 0h-7v-2h7zm0-4h-7v-2h7zm0-4H4V8h16z");
}

</style>
