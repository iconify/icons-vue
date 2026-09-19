<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t9fr1nb7w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:round-near-me" /></template>
<style>
.t9fr1nb7w {
  fill: currentColor;
  d: path("M18.75 3.94L4.07 10.08c-.83.35-.81 1.53.02 1.85L9.43 14a1 1 0 0 1 .57.57l2.06 5.33c.32.84 1.51.86 1.86.03l6.15-14.67c.33-.83-.5-1.66-1.32-1.32");
}

</style>
