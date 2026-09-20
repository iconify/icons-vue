<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bf2fv_qav"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:slides" /></template>
<style>
.bf2fv_qav {
  fill: currentColor;
  d: path("M7 19h10v-7H7Zm1.5-1.5v-4h7v4ZM6 22q-.825 0-1.412-.587Q4 20.825 4 20V4q0-.825.588-1.413Q5.175 2 6 2h8l6 6v12q0 .825-.587 1.413Q18.825 22 18 22Zm7-13h5l-5-5Z");
}

</style>
