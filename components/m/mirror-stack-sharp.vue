<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dy_u6hb4r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:mirror-stack-sharp" /></template>
<style>
.dy_u6hb4r {
  fill: currentColor;
  d: path("M5 21V6.789h8.423V21zm10.616-3.77V4.597h-5.039V3H19v14.23z");
}

</style>
