<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bhmhl7bnr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:spatial-gallery" /></template>
<style>
.bhmhl7bnr {
  fill: currentColor;
  d: path("M9 17.625V12.5h6v5.125zm0-6.096V6.577h6v4.952zm-6.5 0V4.673L8 6.248v5.28zm0 7.837V12.5H8v5.396zm19 0l-5.5-1.47V12.5h5.5zM16 11.529V6.254l5.5-1.475v6.75z");
}

</style>
