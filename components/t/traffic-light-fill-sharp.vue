<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f5pov_bdy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:traffic-light-fill-sharp" /></template>
<style>
.f5pov_bdy {
  fill: currentColor;
  d: path("M6 3a1 1 0 0 1 1-1h10a1 1 0 0 1 1 1v18a1 1 0 0 1-1 1H7a1 1 0 0 1-1-1Zm4.158 3.221a2 2 0 1 0 3.684 1.558a2 2 0 0 0-3.684-1.558m0 5a2 2 0 1 0 3.684 1.558a2 2 0 0 0-3.684-1.558M10 17a2 2 0 1 0 3.999.001A2 2 0 0 0 10 17");
}

</style>
