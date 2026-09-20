<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="po2610bgk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:mobile-landscape-sharp" /></template>
<style>
.po2610bgk {
  fill: currentColor;
  d: path("M2 18V5.923h4.83V5h3.686v.923H22V18zm4.088-5.49q.22-.222.22-.55t-.222-.548t-.549-.22t-.547.222t-.22.549t.22.548t.55.22t.548-.222");
}

</style>
