<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="za2adyd2h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:tv-gen" /></template>
<style>
.za2adyd2h {
  fill: currentColor;
  d: path("M4 21v-2q-.825 0-1.412-.587T2 17V6q0-.825.588-1.412T4 4h16q.825 0 1.413.588T22 6v11q0 .825-.587 1.413T20 19v2h-1l-.65-2H5.675L5 21z");
}

</style>
