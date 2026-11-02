<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bdx6l-7-x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:video-off-fill" /></template>
<style>
.bdx6l-7-x {
  fill: currentColor;
  d: path("m2.707 2.293l19 19a.999.999 0 1 1-1.414 1.414l-4.899-4.898A3 3 0 0 1 13 19H5a3 3 0 0 1-3-3V8c0-.942.439-1.827 1.191-2.394L1.293 3.707a.999.999 0 1 1 1.414-1.414m18.511 15.683L8.243 5H13a3 3 0 0 1 3 3v.382l2.553-1.276c.356-.181.75-.274 1.149-.273C20.924 6.836 22 7.735 22 9v8a1 1 0 0 1-.782.976");
}

</style>
