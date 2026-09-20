<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rdv22s0vg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:mobile-landscape-outline-sharp" /></template>
<style>
.rdv22s0vg {
  fill: currentColor;
  d: path("M2 18V5.923h4.83V5h3.686v.923H22V18zm19-1V6.923H3V17zM3 17V6.923zm3.088-4.49q.22-.222.22-.55t-.222-.548t-.549-.22t-.547.222t-.22.549t.22.548t.55.22t.548-.222");
}

</style>
