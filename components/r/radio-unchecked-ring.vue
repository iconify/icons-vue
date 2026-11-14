<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mjx6aomgy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:radio-unchecked-ring" /></template>
<style>
.mjx6aomgy {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M2.75 12q-.001-3.832 2.708-6.543q2.71-2.71 6.542-2.71t6.542 2.71Q21.251 8.168 21.25 12q.001 3.832-2.708 6.543q-2.71 2.71-6.542 2.71t-6.542-2.71T2.75 12");
}

</style>
