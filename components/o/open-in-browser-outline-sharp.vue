<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pbeh52b0p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:open-in-browser-outline-sharp" /></template>
<style>
.pbeh52b0p {
  fill: currentColor;
  d: path("M4 20V4h16v16h-4.73v-1H19V7H5v12h3.73v1zm7.5 0v-6.304l-2.1 2.1l-.708-.719L12 11.769l3.308 3.308l-.708.72l-2.1-2.1V20z");
}

</style>
