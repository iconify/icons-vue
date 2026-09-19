<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f4eusetal"/><path class="bn6ebpb5p"/><path class="lvlyzzbmm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:outline-9k" /></template>
<style>
.bn6ebpb5p {
  fill: currentColor;
  d: path("M19 3H5c-1.1 0-2 .9-2 2v14c0 1.1.9 2 2 2h14c1.1 0 2-.9 2-2V5c0-1.1-.9-2-2-2m0 16H5V5h14z");
}

.f4eusetal {
  fill: currentColor;
  d: path("M11 14v-4c0-.55-.45-1-1-1H7.5c-.55 0-1 .45-1 1v1.5c0 .55.45 1 1 1h2v1h-3V15H10c.55 0 1-.45 1-1m-1.5-2.5H8V10h1.5z");
}

.lvlyzzbmm {
  fill: currentColor;
  d: path("M14.5 12.75L16.25 15H18l-2.25-3L18 9h-1.75l-1.75 2.25V9H13v6h1.5z");
}

</style>
