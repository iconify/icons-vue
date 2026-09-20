<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a5o82kbby"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:square" /></template>
<style>
.a5o82kbby {
  fill: currentColor;
  d: path("M4 20V4h16v16z");
}

</style>
