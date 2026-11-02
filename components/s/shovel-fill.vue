<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mr3jmzb0c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:shovel-fill" /></template>
<style>
.mr3jmzb0c {
  fill: currentColor;
  d: path("m15.707 4.293l4 4a.999.999 0 1 1-1.414 1.414L17 8.414L12.414 13l1.293 1.293a2.414 2.414 0 0 1 0 3.414l-1 1A1 1 0 0 1 12 19H8a3 3 0 0 1-3-3v-4c0-.265.105-.52.293-.707l1-1a2.414 2.414 0 0 1 3.414 0L11 11.586L15.586 7l-1.293-1.293a.999.999 0 1 1 1.414-1.414");
}

</style>
