<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ylbep6b9q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:outline-edgesensor-high" /></template>
<style>
.ylbep6b9q {
  fill: currentColor;
  d: path("M3 7h2v7H3zm-3 3h2v7H0zm22-3h2v7h-2zm-3 3h2v7h-2zm-3-7.99L8 2c-1.1 0-2 .9-2 2v16c0 1.1.9 2 2 2h8c1.1 0 2-.9 2-2V4c0-1.1-.9-1.99-2-1.99M16 20H8v-1h8zm0-3H8V7h8zM8 5V4h8v1z");
}

</style>
