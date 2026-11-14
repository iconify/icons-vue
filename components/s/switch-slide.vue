<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vyozksb9c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:switch-slide" /></template>
<style>
.vyozksb9c {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M16.5 7.25h-9q-1.968 0-3.359 1.391T2.75 12t1.391 3.359T7.5 16.75h9q1.968 0 3.359-1.391T21.25 12t-1.391-3.359T16.5 7.25m-9 2h1q2.75 0 2.75 2.75T8.5 14.75h-1q-2.75 0-2.75-2.75T7.5 9.25");
}

</style>
