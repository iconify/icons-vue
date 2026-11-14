<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fgo3jbbpp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:signal-edge" /></template>
<style>
.fgo3jbbpp {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M20 2.75q2 0 2 2v14.5q0 2-2 2t-2-2V4.75q0-2 2-2m-3.25 6q0-2-2-2t-2 2v10.5q0 2 2 2t2-2zm-7.25 2q2 0 2 2v6.5q0 2-2 2t-2-2v-6.5q0-2 2-2m-3.25 6q0-2-2-2t-2 2v2.5q0 2 2 2t2-2z");
}

</style>
