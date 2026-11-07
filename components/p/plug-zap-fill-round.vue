<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="haedzcb6d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:plug-zap-fill-round" /></template>
<style>
.haedzcb6d {
  fill: currentColor;
  d: path("M5 3a1 1 0 0 1 2 0v3h2V3a1 1 0 0 1 2 0v3.416A5 5 0 0 1 14 11v2a5 5 0 0 1-5 5v3a1 1 0 0 1-2 0v-3a5 5 0 0 1-5-5v-2c0-1.99 1.175-3.79 3-4.584Zm16 8a1 1 0 0 1 .857 1.514l-3 5a1 1 0 0 1-1.371.343a1 1 0 0 1-.343-1.371L19.234 13H17a1 1 0 0 1-.857-1.514l3-5a.998.998 0 0 1 1.731.029a1 1 0 0 1-.017.999L18.766 11Z");
}

</style>
