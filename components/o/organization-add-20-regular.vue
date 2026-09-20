<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="k2iw9mm0w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:organization-add-20-regular" /></template>
<style>
.k2iw9mm0w {
  fill: currentColor;
  d: path("M14.5 10a4.5 4.5 0 1 1 0 9a4.5 4.5 0 0 1 0-9M10 2a3.001 3.001 0 0 1 .5 5.96V9.5h1.709a5.5 5.5 0 0 0-1.482 1H6.5a.5.5 0 0 0-.5.5v1.041a3.002 3.002 0 0 1-.499 5.96A3 3 0 0 1 5 12.042V11a1.5 1.5 0 0 1 1.5-1.5h3V7.96A3.002 3.002 0 0 1 10 2M5.501 13a2.001 2.001 0 1 0 0 4.002a2.001 2.001 0 0 0 0-4.002m8.999-1a.5.5 0 0 0-.5.5V14h-1.5a.5.5 0 0 0 0 1H14v1.5a.5.5 0 0 0 1 0V15h1.5a.5.5 0 0 0 0-1H15v-1.5a.5.5 0 0 0-.5-.5M10 3a2.001 2.001 0 1 0 0 4.002A2.001 2.001 0 0 0 10 3");
}

</style>
