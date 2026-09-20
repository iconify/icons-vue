<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<path class="tu7yv_par"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:presenter-28-regular" /></template>
<style>
.tu7yv_par {
  fill: currentColor;
  d: path("M24.25 14a.75.75 0 0 1 .51 1.3L19 20.648v2.602A2.75 2.75 0 0 1 16.25 26h-4.5A2.75 2.75 0 0 1 9 23.25v-2.602L3.24 15.3a.751.751 0 0 1 .51-1.3zm-13.99 5.772a.75.75 0 0 1 .24.55v2.928l.007.128A1.25 1.25 0 0 0 11.75 24.5h4.5c.69 0 1.25-.56 1.25-1.25v-2.929a.75.75 0 0 1 .24-.55l4.6-4.271H5.66zm5.99-9.272a2.75 2.75 0 0 1 2.737 2.5h-1.512c-.116-.57-.62-1-1.225-1h-4.5a1.25 1.25 0 0 0-1.225 1H9.012a2.75 2.75 0 0 1 2.737-2.5zM14 2a3.5 3.5 0 1 1 0 7a3.5 3.5 0 0 1 0-7m0 1.5a2 2 0 1 0 0 4a2 2 0 0 0 0-4");
}

</style>
