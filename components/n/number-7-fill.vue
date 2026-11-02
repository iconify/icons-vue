<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qawi-zbwl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:number-7-fill" /></template>
<style>
.qawi-zbwl {
  fill: currentColor;
  d: path("M16 3a.998.998 0 0 1 .97 1.243l-4 16a.999.999 0 1 1-1.94-.486L14.719 5H8a1 1 0 0 1 0-2Z");
}

</style>
