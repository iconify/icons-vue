<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pycbi7pqw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:scan-sharp" /></template>
<style>
.pycbi7pqw {
  fill: currentColor;
  d: path("M13 9h5l-5-5zM4 22v-5h16v5zm-3-7v-2h22v2zm3-4V2h10l6 6v3z");
}

</style>
