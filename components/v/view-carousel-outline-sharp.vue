<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v6twkgk3g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:view-carousel-outline-sharp" /></template>
<style>
.v6twkgk3g {
  fill: currentColor;
  d: path("M2 17V7h4v10zm5 2V5h10v14zm11-2V7h4v10zm-9 0h6V7H9zm3-5");
}

</style>
