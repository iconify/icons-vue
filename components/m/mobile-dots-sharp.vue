<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lntxbzb-s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:mobile-dots-sharp" /></template>
<style>
.lntxbzb-s {
  fill: currentColor;
  d: path("M6.751 12.52q.21-.209.21-.52t-.21-.52t-.52-.21t-.52.21q-.211.209-.211.52t.21.52t.52.21t.521-.21m3.846 0q.21-.209.21-.52t-.21-.52q-.209-.21-.52-.21q-.31 0-.52.21q-.21.209-.21.52t.209.52t.52.21t.521-.21m3.846 0q.21-.209.21-.52t-.209-.52t-.52-.21t-.521.21q-.21.209-.21.52t.21.52q.209.21.52.21q.31 0 .52-.21m3.847 0q.21-.209.21-.52t-.21-.52t-.52-.21t-.521.21q-.21.209-.21.52t.21.52t.52.21t.52-.21M2 18V5.923h4.83V5h3.686v.923H22V18z");
}

</style>
