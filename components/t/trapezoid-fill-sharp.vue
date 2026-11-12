<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tufgjj3gk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:trapezoid-fill-sharp" /></template>
<style>
.tufgjj3gk {
  fill: currentColor;
  d: path("M21.217 6.024A1 1 0 0 1 22 7v10a1 1 0 0 1-.783.976l-18 4A1 1 0 0 1 2 21V3a1.002 1.002 0 0 1 1.217-.976Z");
}

</style>
