<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="iigm4ze1s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:youpic" /></template>
<style>
.iigm4ze1s {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M15.25 5.5H6.5v37h8.75m17.5 0h8.75v-37h-8.75m-1.375 7.75L24 24l-7.375-10.75M24 34.75V24");
}

</style>
