<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rnwchjbdm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:tv-gen-sharp" /></template>
<style>
.rnwchjbdm {
  fill: currentColor;
  d: path("M4 21v-2H2V4h20v15h-2v2h-1l-.65-2H5.675L5 21z");
}

</style>
