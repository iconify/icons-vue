<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rysd8ybww"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:position-bottom-right-sharp" /></template>
<style>
.rysd8ybww {
  fill: currentColor;
  d: path("M9.385 16.808h8v-2h-8zM4 20V4h16v16z");
}

</style>
