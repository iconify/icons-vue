<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hi7ghd54n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:reptile-hide" /></template>
<style>
.hi7ghd54n {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M5.5 5.25q-3.25 0-3.25 6.75t3.25 6.75h13q3.25 0 3.25-6.75T18.5 5.25zM17.75 15q0-3.75-3.75-3.75T10.25 15v2.25H7.842q.908-1.682.908-5.25t-.908-5.25H18.5q1.75 0 1.75 5.25t-1.75 5.25h-.75zm-1.5 2.25h-4.5V15q0-2.25 2.25-2.25T16.25 15z");
}

</style>
