<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ivomhabac"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:stay-current-landscape-sharp" /></template>
<style>
.ivomhabac {
  fill: currentColor;
  d: path("M2 18V6h20v12zm3.5-1h13V7h-13z");
}

</style>
