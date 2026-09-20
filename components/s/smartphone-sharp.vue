<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jwizc5bwk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:smartphone-sharp" /></template>
<style>
.jwizc5bwk {
  fill: currentColor;
  d: path("M6 22V2h12v20zm1-3.5h10v-13H7z");
}

</style>
