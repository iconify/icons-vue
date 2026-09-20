<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mngza6bdp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:unfloat-portrait-outline-sharp" /></template>
<style>
.mngza6bdp {
  fill: currentColor;
  d: path("M4 22V2h16v11h-2V4H6v16h7v2Zm10.5-10.925L11.425 8H14V6H8v6h2V9.4l3.075 3.1ZM15 22v-7h5v7Zm-3-10Z");
}

</style>
