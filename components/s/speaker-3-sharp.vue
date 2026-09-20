<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="alppr7vxf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:speaker-3-sharp" /></template>
<style>
.alppr7vxf {
  fill: currentColor;
  d: path("M8.692 21v-1H4.981V3H19v17h-3.73v1z");
}

</style>
