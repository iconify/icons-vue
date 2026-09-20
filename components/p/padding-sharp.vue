<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e_diuibdp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:padding-sharp" /></template>
<style>
.e_diuibdp {
  fill: currentColor;
  d: path("M7 9h2V7H7zm4 0h2V7h-2zm4 0h2V7h-2zM3 21V3h18v18z");
}

</style>
