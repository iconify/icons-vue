<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="onr1mpmxe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:triangle-left-20-regular" /></template>
<style>
.onr1mpmxe {
  fill: currentColor;
  d: path("M2.786 11.318c-1.048-.567-1.048-2.07 0-2.638l11.998-6.5A1.5 1.5 0 0 1 17 3.5v12.999a1.5 1.5 0 0 1-2.215 1.319zm.476-1.758a.5.5 0 0 0 0 .879l11.998 6.5a.5.5 0 0 0 .739-.44v-13a.5.5 0 0 0-.739-.439z");
}

</style>
