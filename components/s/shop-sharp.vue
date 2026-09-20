<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g09oe1bdi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:shop-sharp" /></template>
<style>
.g09oe1bdi {
  fill: currentColor;
  d: path("M2 21V6h6V2h8v4h6v15zm8-15h4V4h-4zm-.5 12l7-4.5l-7-4.5z");
}

</style>
