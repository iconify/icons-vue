<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x1gde_igh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:panel-right-open-fill-sharp" /></template>
<style>
.x1gde_igh {
  fill: currentColor;
  d: path("M3 4a1 1 0 0 1 1-1h16a1 1 0 0 1 1 1v16a1 1 0 0 1-1 1H4a1 1 0 0 1-1-1Zm11 1H5v14h9Zm-2.293 4.707L9.414 12l2.293 2.293a.999.999 0 1 1-1.414 1.414l-3-3a.997.997 0 0 1 0-1.414l3-3a.999.999 0 1 1 1.414 1.414");
}

</style>
