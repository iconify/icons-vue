<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sss6m4nal"/><path class="gzouen2xt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:zoom-in" /></template>
<style>
.gzouen2xt {
  fill: currentColor;
  d: path("M12 10h-2v2H9v-2H7V9h2V7h1v2h2z");
}

.sss6m4nal {
  fill: currentColor;
  d: path("M15.5 14h-.79l-.28-.27A6.47 6.47 0 0 0 16 9.5A6.5 6.5 0 1 0 9.5 16c1.61 0 3.09-.59 4.23-1.57l.27.28v.79l5 4.99L20.49 19zm-6 0C7.01 14 5 11.99 5 9.5S7.01 5 9.5 5S14 7.01 14 9.5S11.99 14 9.5 14");
}

</style>
