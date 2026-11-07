<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pi8s7uudv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:packages-fill-round" /></template>
<style>
.pi8s7uudv {
  fill: currentColor;
  d: path("m17.5 10.257l2.842 1.421A3 3 0 0 1 22 14.361v3.153a3 3 0 0 1-1.658 2.683l-2.5 1.25a3 3 0 0 1-2.684 0L12 19.868l-3.158 1.579a3 3 0 0 1-2.684 0l-2.5-1.25A3 3 0 0 1 2 17.514v-3.153a3 3 0 0 1 1.658-2.683L6.5 10.257V6.486a3 3 0 0 1 1.658-2.683l2.5-1.25a3 3 0 0 1 2.684 0l2.5 1.25A3 3 0 0 1 17.5 6.486Zm-5.053-5.915a1 1 0 0 0-.894 0l-.923.461a.5.5 0 0 0 0 .894l1.37.685l1.37-.685a.5.5 0 0 0 0-.894ZM15.5 7.868a.62.62 0 0 0-.894-.553L13 8.118v3.389l2.5-1.25Zm-8 4.125l-1.37.685a.5.5 0 0 0 0 .894l1.37.685l2.264-1.132Zm9 0l-2.264 1.132l2.264 1.132l1.369-.685a.499.499 0 0 0 0-.894Zm-5.5 2.75l-2.5 1.25v2.389a.62.62 0 0 0 .894.553L11 18.132Zm8.106.447l-1.606.803v2.389a.62.62 0 0 0 .894.553l1.053-.527a1 1 0 0 0 .553-.894v-1.771a.62.62 0 0 0-.894-.553");
}

</style>
