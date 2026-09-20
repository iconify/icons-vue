<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xk4jygcos"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:smartphone-sharp" /></template>
<style>
.xk4jygcos {
  fill: currentColor;
  d: path("M5 23V1h14v22zm2-5h10V6H7z");
}

</style>
