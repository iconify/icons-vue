<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="imrn2rwow"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:mms-sharp" /></template>
<style>
.imrn2rwow {
  fill: currentColor;
  d: path("M6 14h12l-3.75-5l-3 4L9 10zm-4 8V2h20v16H6z");
}

</style>
