<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f0z7yppkn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-spoke" /></template>
<style>
.f0z7yppkn {
  fill: currentColor;
  d: path("M16 7c0 2.21-1.79 4-4 4S8 9.21 8 7s1.79-4 4-4s4 1.79 4 4m-9 6c-2.21 0-4 1.79-4 4s1.79 4 4 4s4-1.79 4-4s-1.79-4-4-4m10 0c-2.21 0-4 1.79-4 4s1.79 4 4 4s4-1.79 4-4s-1.79-4-4-4");
}

</style>
