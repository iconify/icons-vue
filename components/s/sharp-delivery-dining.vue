<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wonq14b-m"/><path class="bdaznj-fp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-delivery-dining" /></template>
<style>
.bdaznj-fp {
  fill: currentColor;
  d: path("M5 6h5v2H5zm14 7c-1.66 0-3 1.34-3 3s1.34 3 3 3s3-1.34 3-3s-1.34-3-3-3m0 4c-.55 0-1-.45-1-1s.45-1 1-1s1 .45 1 1s-.45 1-1 1");
}

.wonq14b-m {
  fill: currentColor;
  d: path("M19 10.35V5h-5v2h3v2.65L13.52 14H10V9H2v7h2c0 1.66 1.34 3 3 3s3-1.34 3-3h4.48zM7 17c-.55 0-1-.45-1-1h2c0 .55-.45 1-1 1");
}

</style>
