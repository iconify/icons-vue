<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="glbtgzbrq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:plug-zap-fill" /></template>
<style>
.glbtgzbrq {
  fill: currentColor;
  d: path("M5 3a1 1 0 0 1 2 0v3h2V3a1 1 0 0 1 2 0v3a3 3 0 0 1 3 3v6a3 3 0 0 1-3 3H9v3a1 1 0 0 1-2 0v-3H5a3 3 0 0 1-3-3V9a3 3 0 0 1 3-3Zm16 8a1 1 0 0 1 .857 1.514l-3 5a1 1 0 0 1-1.371.343a1 1 0 0 1-.343-1.371L19.234 13H17a1 1 0 0 1-.857-1.514l3-5a.998.998 0 0 1 1.731.029a1 1 0 0 1-.017.999L18.766 11Z");
}

</style>
