<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d8tx_dbax"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:mobile-off-outline-sharp" /></template>
<style>
.d8tx_dbax {
  fill: currentColor;
  d: path("M20.5 23.3L.7 3.5l1.4-1.4l19.8 19.8zM19 16.2l-2-2V3H5V1h14v5.1h1v4.8h-1zM12.713 5.713Q13 5.425 13 5t-.288-.712T12 4t-.712.288T11 5t.288.713T12 6t.713-.288M5 23V5l2 2v14h10v-4l2 2v4zm8.9-11.7");
}

</style>
