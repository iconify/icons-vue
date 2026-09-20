<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yysb2trkq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:straighten-sharp" /></template>
<style>
.yysb2trkq {
  fill: currentColor;
  d: path("M2 18V6h5v6h2V6h2v6h2V6h2v6h2V6h5v12z");
}

</style>
