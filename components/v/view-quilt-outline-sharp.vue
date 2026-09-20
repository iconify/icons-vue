<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l5zghobyw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:view-quilt-outline-sharp" /></template>
<style>
.l5zghobyw {
  fill: currentColor;
  d: path("M4 18V6h16v12zm5.94-6.5H19V7H9.94zm5.024 5.5H19v-4.5h-4.036zM9.94 17h4.022v-4.5h-4.02zM5 17h3.94V7H5z");
}

</style>
