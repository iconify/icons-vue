<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="oe9-zdl7a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:user-check-thin" /></template>
<style>
.oe9-zdl7a {
  fill: currentColor;
  d: path("M133.17 158.84a64 64 0 1 0-50.34 0c-23.76 5.46-45.18 18.69-61.89 38.59a4 4 0 1 0 6.12 5.14C48 177.7 76.71 164 108 164s60 13.7 80.94 38.57a4 4 0 0 0 6.12-5.14c-16.71-19.9-38.13-33.13-61.89-38.59M52 100a56 56 0 1 1 56 56a56.06 56.06 0 0 1-56-56m198.83 30.83l-32 32a4 4 0 0 1-5.66 0l-16-16a4 4 0 0 1 5.66-5.66L216 154.34l29.17-29.17a4 4 0 1 1 5.66 5.66");
}

</style>
