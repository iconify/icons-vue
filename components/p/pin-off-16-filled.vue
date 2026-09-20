<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="r4w6xw0xr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:pin-off-16-filled" /></template>
<style>
.r4w6xw0xr {
  fill: currentColor;
  d: path("m9.56 10.267l4.586 4.587a.5.5 0 0 0 .708-.708l-13-13a.5.5 0 1 0-.708.708l4.586 4.585l-.08.15l-2.81.937a.5.5 0 0 0-.196.828L4.793 10.5l-2.647 2.646L2 14l.853-.146L5.5 11.207l2.146 2.147a.5.5 0 0 0 .828-.196l.937-2.811zm3.63-1.943l-1.788.957l-4.686-4.687l.957-1.796a1.5 1.5 0 0 1 2.386-.353l3.485 3.498a1.5 1.5 0 0 1-.354 2.381");
}

</style>
