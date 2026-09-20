<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="xk_vmob4f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:syringe-light" /></template>
<style>
.xk_vmob4f {
  fill: currentColor;
  d: path("m236.24 67.76l-48-48a6 6 0 0 0-8.48 8.48L199.51 48L168 79.51l-35.76-35.75a6 6 0 1 0-8.48 8.48l7.75 7.76l-85.41 85.41a13.94 13.94 0 0 0-4.1 9.9v50.2l-22.24 22.25a6 6 0 1 0 8.48 8.48L50.49 214h50.2a13.94 13.94 0 0 0 9.9-4.1L196 124.49l7.76 7.75a6 6 0 0 0 8.48-8.48L176.49 88L208 56.49l19.76 19.75a6 6 0 0 0 8.48-8.48M102.1 201.41a2 2 0 0 1-1.41.59H54v-46.69a2 2 0 0 1 .59-1.41L74 134.49l21.76 21.75a6 6 0 1 0 8.48-8.48L82.49 126L98 110.49l21.76 21.75a6 6 0 0 0 8.48-8.48L106.49 102L140 68.49L187.51 116Z");
}

</style>
