<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h0rvc-bsy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:ripples-sharp" /></template>
<style>
.h0rvc-bsy {
  fill: currentColor;
  d: path("M14.127 5q-.294.45-.46.953T13.5 7q0 1.458 1.021 2.479T17 10.5q.544 0 1.047-.166q.503-.167.953-.461V5zM4 20V4h16v16z");
}

</style>
