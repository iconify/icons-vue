<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k_2k3_b1h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:position-top-right-sharp" /></template>
<style>
.k_2k3_b1h {
  fill: currentColor;
  d: path("M9.385 9.192h8v-2h-8zM4 20V4h16v16z");
}

</style>
