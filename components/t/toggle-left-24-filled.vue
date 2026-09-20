<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l1_woybrd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:toggle-left-24-filled" /></template>
<style>
.l1_woybrd {
  fill: currentColor;
  d: path("M17 7a5 5 0 0 1 0 10H7A5 5 0 0 1 7 7zm-9.75 7.5a2.5 2.5 0 1 0 0-5a2.5 2.5 0 0 0 0 5");
}

</style>
