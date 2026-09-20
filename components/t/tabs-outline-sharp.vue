<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u1f1qob1f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:tabs-outline-sharp" /></template>
<style>
.u1f1qob1f {
  fill: currentColor;
  d: path("M4 20V4h16v16zm1-1h14v-7.615H5zm0-8.615h14V5H5zM12 8h6V6h-6zm-7 2.385V5z");
}

</style>
