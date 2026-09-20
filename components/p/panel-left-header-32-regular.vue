<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ewdx-lbiu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:panel-left-header-32-regular" /></template>
<style>
.ewdx-lbiu {
  fill: currentColor;
  d: path("M6.5 4A4.5 4.5 0 0 0 2 8.5v15A4.5 4.5 0 0 0 6.5 28h19a4.5 4.5 0 0 0 4.5-4.5v-15A4.5 4.5 0 0 0 25.5 4zm5.5 9h16v10.5a2.5 2.5 0 0 1-2.5 2.5H12zm16-2H12V6h13.5A2.5 2.5 0 0 1 28 8.5zM6.5 6H10v20H6.5A2.5 2.5 0 0 1 4 23.5v-15A2.5 2.5 0 0 1 6.5 6");
}

</style>
