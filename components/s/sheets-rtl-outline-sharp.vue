<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o646ci6-o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:sheets-rtl-outline-sharp" /></template>
<style>
.o646ci6-o {
  fill: currentColor;
  d: path("M5 12.577v-10h14v10zm1-5.5h5.5v-3.5H6zm6.5 0H18v-3.5h-5.5zm-6.5 4.5h5.5v-3.5H6zm6.5 0H18v-3.5h-5.5zM7 20.712l-3.288-3.289L7 14.135l.708.688l-2.075 2.1H19.5v1H5.633l2.075 2.1z");
}

</style>
