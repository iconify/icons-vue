<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vdcntmbns"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:play-fill" /></template>
<style>
.vdcntmbns {
  fill: currentColor;
  d: path("M19.543 9.428a2.998 2.998 0 0 1 0 5.144l-10 6A2.998 2.998 0 0 1 5 18V6a3 3 0 0 1 4.543-2.572Z");
}

</style>
