<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nnqld5b7m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:volume-minus-fill-sharp" /></template>
<style>
.nnqld5b7m {
  fill: currentColor;
  d: path("M12 4v16a1.002 1.002 0 0 1-1.707.707L6.586 17H3a1 1 0 0 1-1-1V8a1 1 0 0 1 1-1h3.586l3.707-3.707A1 1 0 0 1 12 4m9 7a1 1 0 0 1 0 2h-6a1 1 0 0 1 0-2Z");
}

</style>
