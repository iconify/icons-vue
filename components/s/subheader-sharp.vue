<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bopwhvbfp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:subheader-sharp" /></template>
<style>
.bopwhvbfp {
  fill: currentColor;
  d: path("M6 10h9V7H6zM3 21V3h18v18z");
}

</style>
