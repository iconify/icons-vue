<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zr46llbys"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-night-shelter" /></template>
<style>
.zr46llbys {
  fill: currentColor;
  d: path("M12 3L4 9v12h16V9zm-2.25 9.5a1.25 1.25 0 1 1 0 2.5a1.25 1.25 0 0 1 0-2.5M17 18h-1v-1.5H8V18H7v-7h1v4.5h3.5V12H17z");
}

</style>
