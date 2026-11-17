<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k0eqjyvoe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:more-diagonal-alt-fill-round" /></template>
<style>
.k0eqjyvoe {
  fill: currentColor;
  d: path("M5.158 6.221a2 2 0 1 1 3.684 1.558a2 2 0 0 1-3.684-1.558m5 5a2 2 0 1 1 3.684 1.558a2 2 0 0 1-3.684-1.558m5 5a2 2 0 1 1 3.684 1.558a2 2 0 0 1-3.684-1.558");
}

</style>
