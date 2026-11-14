<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gyubb6ncb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:pagination-dots" /></template>
<style>
.gyubb6ncb {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M4.5 9.75h4q2.25 0 2.25 2.25T8.5 14.25h-4q-2.25 0-2.25-2.25q0-.932.659-1.591T4.5 9.75M14 10q-2 0-2 2t2 2t2-2t-2-2m3.5 2q0-2 2-2t2 2t-2 2t-2-2");
}

</style>
