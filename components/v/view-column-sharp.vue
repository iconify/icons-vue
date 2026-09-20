<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uq220ihex"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:view-column-sharp" /></template>
<style>
.uq220ihex {
  fill: currentColor;
  d: path("M4 18V6h4.825v12zm5.594 0V6H14.4v12zm5.575 0V6h4.825v12z");
}

</style>
