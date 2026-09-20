<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="rz5otx0go"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:speaker-low-thin" /></template>
<style>
.rz5otx0go {
  fill: currentColor;
  d: path("M153.76 28.41a4 4 0 0 0-4.22.43L78.63 84H32a12 12 0 0 0-12 12v64a12 12 0 0 0 12 12h46.63l70.91 55.16a4.07 4.07 0 0 0 2.46.84a3.9 3.9 0 0 0 1.76-.41A4 4 0 0 0 156 224V32a4 4 0 0 0-2.24-3.59M28 160V96a4 4 0 0 1 4-4h44v72H32a4 4 0 0 1-4-4m120 55.82L84 166V90l64-49.78ZM204 128a36 36 0 0 1-9 23.82a4 4 0 1 1-6-5.3a28 28 0 0 0 0-37a4 4 0 0 1 6-5.28a36 36 0 0 1 9 23.76");
}

</style>
