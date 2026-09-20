<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i-uji_4ik"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:toggle-right-24-filled" /></template>
<style>
.i-uji_4ik {
  fill: currentColor;
  d: path("M7 7a5 5 0 0 0 0 10h10a5 5 0 0 0 0-10zm9.75 7.5a2.5 2.5 0 1 1 0-5a2.5 2.5 0 0 1 0 5");
}

</style>
