<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="smjywgqfj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-keyboard-control-key" /></template>
<style>
.smjywgqfj {
  fill: currentColor;
  d: path("m5 12l1.41 1.41L12 7.83l5.59 5.58L19 12l-7-7z");
}

</style>
