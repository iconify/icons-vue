<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n8t8eji2c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:view-carousel-sharp" /></template>
<style>
.n8t8eji2c {
  fill: currentColor;
  d: path("M2 17V7h4v10zm5 2V5h10v14zm11-2V7h4v10z");
}

</style>
