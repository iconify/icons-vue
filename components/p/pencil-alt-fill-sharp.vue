<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o97l-i27c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:pencil-alt-fill-sharp" /></template>
<style>
.o97l-i27c {
  fill: currentColor;
  d: path("m3.293 15.293l12-12a1 1 0 0 1 1.414 0l4 4a1 1 0 0 1 0 1.414l-12 12A1 1 0 0 1 8 21H4a1 1 0 0 1-1-1v-4c0-.265.105-.52.293-.707");
}

</style>
