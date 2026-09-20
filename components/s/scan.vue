<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rfs5b2ouv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:scan" /></template>
<style>
.rfs5b2ouv {
  fill: currentColor;
  d: path("M13 9h5l-5-5zM6 22q-.825 0-1.412-.587T4 20v-3h16v3q0 .825-.587 1.413T18 22zm-5-7v-2h22v2zm3-4V4q0-.825.588-1.412T6 2h8l6 6v3z");
}

</style>
