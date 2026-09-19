<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="alru2abri"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:round-keyboard-backspace" /></template>
<style>
.alru2abri {
  fill: currentColor;
  d: path("M20 11H6.83l2.88-2.88A.996.996 0 1 0 8.3 6.71L3.71 11.3a.996.996 0 0 0 0 1.41L8.3 17.3a.996.996 0 1 0 1.41-1.41L6.83 13H20c.55 0 1-.45 1-1s-.45-1-1-1");
}

</style>
