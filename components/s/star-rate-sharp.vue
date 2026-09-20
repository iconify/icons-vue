<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uow__4bme"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:star-rate-sharp" /></template>
<style>
.uow__4bme {
  fill: currentColor;
  d: path("m7.69 18.346l1.614-5.33L5.115 10h5.216L12 4.462L13.67 10h5.215l-4.189 3.016l1.614 5.33L12 15.07z");
}

</style>
