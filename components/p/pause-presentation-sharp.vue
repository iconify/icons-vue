<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x8ry8s0bm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:pause-presentation-sharp" /></template>
<style>
.x8ry8s0bm {
  fill: currentColor;
  d: path("M9.808 15.5h1v-7h-1zm3.384 0h1v-7h-1zM3 19V5h18v14z");
}

</style>
