<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="qccz3blph"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:text-quote-16-regular" /></template>
<style>
.qccz3blph {
  fill: currentColor;
  d: path("M11 4a1 1 0 1 1 0 2a1 1 0 0 1 0-2m.885 2.794c-.23 1.592-.852 2.966-2.239 4.352a.5.5 0 0 0 .708.708C12.473 9.734 13 7.592 13 5a2 2 0 1 0-1.115 1.794M5 4a1 1 0 1 1 0 2a1 1 0 0 1 0-2m.885 2.794c-.23 1.592-.852 2.966-2.239 4.352a.5.5 0 0 0 .708.708C6.473 9.734 7 7.592 7 5a2 2 0 1 0-1.115 1.794");
}

</style>
