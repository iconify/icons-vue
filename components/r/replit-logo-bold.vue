<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="lqa__wb-c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:replit-logo-bold" /></template>
<style>
.lqa__wb-c {
  fill: currentColor;
  d: path("M216 84h-60V40a20 20 0 0 0-20-20H72a20 20 0 0 0-20 20v48a20 20 0 0 0 20 20h60v40H72a20 20 0 0 0-20 20v48a20 20 0 0 0 20 20h64a20 20 0 0 0 20-20v-44h60a20 20 0 0 0 20-20v-48a20 20 0 0 0-20-20m-84 128H76v-40h56Zm0-128H76V44h56Zm80 64h-56v-40h56Z");
}

</style>
