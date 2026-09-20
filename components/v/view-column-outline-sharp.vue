<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wysxy5bia"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:view-column-outline-sharp" /></template>
<style>
.wysxy5bia {
  fill: currentColor;
  d: path("M3.025 19V5H21v14zM5 17h3.325V7H5zm5.325 0h3.325V7h-3.325zm5.325 0h3.325V7H15.65z");
}

</style>
