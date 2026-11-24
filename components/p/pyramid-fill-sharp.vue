<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lb8u9_b8o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:pyramid-fill-sharp" /></template>
<style>
.lb8u9_b8o {
  fill: currentColor;
  d: path("m1.168 19.445l10-15a1 1 0 0 1 1.664 0l10 15A1 1 0 0 1 22 21H2a1 1 0 0 1-.832-1.555M3.869 19h10.829L11.604 7.397Z");
}

</style>
