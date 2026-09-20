<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ft58iksrl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:post-rounded" /></template>
<style>
.ft58iksrl {
  fill: currentColor;
  d: path("M18.385 20H5.615q-.666 0-1.14-.475T4 18.386V5.615q0-.666.475-1.14T5.615 4h12.77q.666 0 1.14.475T20 5.615v12.77q0 .666-.475 1.14t-1.14.475M5.768 13.962H18.23v-1.116H5.769zm0 2.692H18.23v-.885H5.769z");
}

</style>
