<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="np_ea7b1t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:paperclip-horizontal-thin" /></template>
<style>
.np_ea7b1t {
  fill: currentColor;
  d: path("M244 128a52.06 52.06 0 0 1-52 52H48a36 36 0 0 1 0-72h144a20 20 0 0 1 0 40H80a4 4 0 0 1 0-8h112a12 12 0 0 0 0-24H48a28 28 0 0 0 0 56h144a44 44 0 0 0 0-88H80a4 4 0 0 1 0-8h112a52.06 52.06 0 0 1 52 52");
}

</style>
