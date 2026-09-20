<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a34b0acmk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:military-tech-sharp" /></template>
<style>
.a34b0acmk {
  fill: currentColor;
  d: path("m8.9 22l1.2-3.8L7 16h3.8l.7-2.3L7 11.05V2h10v9.05l-4.5 2.65l.7 2.3H17l-3.1 2.2l1.2 3.8l-3.1-2.35zM12 11.65l1-.6V4h-2v7.05z");
}

</style>
