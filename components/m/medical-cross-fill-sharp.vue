<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fgq4y2bcn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:medical-cross-fill-sharp" /></template>
<style>
.fgq4y2bcn {
  fill: currentColor;
  d: path("M15 3v3.804l3.294-1.902a1 1 0 0 1 1.366.366l2 3.464a1 1 0 0 1-.366 1.366L18 12l3.294 1.902a1 1 0 0 1 .366 1.366l-2 3.464a1 1 0 0 1-1.366.366L15 17.196V21a1 1 0 0 1-1 1h-4a1 1 0 0 1-1-1v-3.804l-3.294 1.902a.997.997 0 0 1-1.366-.366l-2-3.464a1 1 0 0 1 .366-1.366L6 12l-3.294-1.902a1 1 0 0 1-.366-1.366l2-3.464a1 1 0 0 1 1.366-.366L9 6.804V3a1 1 0 0 1 1-1h4a1 1 0 0 1 1 1");
}

</style>
