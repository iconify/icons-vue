<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ifw4kjb2r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:video-library-sharp" /></template>
<style>
.ifw4kjb2r {
  fill: currentColor;
  d: path("m11.5 14.5l7-4.5l-7-4.5zM6 18V2h16v16zm-4 4V6h2v14h14v2z");
}

</style>
