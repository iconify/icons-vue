<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mzv-ocbvo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:view-column-outline-sharp" /></template>
<style>
.mzv-ocbvo {
  fill: currentColor;
  d: path("M4.006 18V6H20v12zM5 17h3.998V7H5zm4.998 0h3.998V7H9.998zm4.998 0h3.998V7h-3.998z");
}

</style>
