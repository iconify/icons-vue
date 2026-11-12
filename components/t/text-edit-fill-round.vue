<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bzsggnbhl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:text-edit-fill-round" /></template>
<style>
.bzsggnbhl {
  fill: currentColor;
  d: path("m15 4.586l1.293-1.293a2.414 2.414 0 0 1 3.414 0l1 1a2.414 2.414 0 0 1 0 3.414L19.414 9ZM8 12c0-.265.105-.52.293-.707L13.586 6L18 10.414l-5.293 5.293A1 1 0 0 1 12 16H9a1 1 0 0 1-1-1Zm-5.707 8.293l3-3a1 1 0 0 1 1.414 0l3 3a.999.999 0 1 1-1.414 1.414L6 19.414l-2.293 2.293a.999.999 0 1 1-1.414-1.414M21 20a1 1 0 0 1 0 2h-8a1 1 0 0 1 0-2Z");
}

</style>
