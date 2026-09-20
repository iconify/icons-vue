<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="mwre4zh2c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:pentagon-20-filled" /></template>
<style>
.mwre4zh2c {
  fill: currentColor;
  d: path("M11.761 1.658a2.5 2.5 0 0 0-3.37-.01L2.822 6.7a2.5 2.5 0 0 0-.672 2.702l2.149 5.947a2.5 2.5 0 0 0 2.351 1.65h6.827a2.5 2.5 0 0 0 2.369-1.702L17.87 9.28a2.5 2.5 0 0 0-.68-2.64z");
}

</style>
