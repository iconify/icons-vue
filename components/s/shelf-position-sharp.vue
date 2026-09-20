<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y_2g1tawm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:shelf-position-sharp" /></template>
<style>
.y_2g1tawm {
  fill: currentColor;
  d: path("M3 21v-5h18v5zm13.5-7V3H21v11zM3 14V3h4.5v11zm6.5 0V3h5v11z");
}

</style>
