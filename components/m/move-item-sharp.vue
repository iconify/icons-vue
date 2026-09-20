<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="btf4m5b2w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:move-item-sharp" /></template>
<style>
.btf4m5b2w {
  fill: currentColor;
  d: path("M20.15 13H8v-2h12.15L18.6 9.45L20 8l4 4l-4 4l-1.4-1.45zM15 9V5H5v14h10v-4h2v6H3V3h14v6z");
}

</style>
