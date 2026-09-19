<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="p7p-t6b_g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:tabby" /></template>
<style>
.p7p-t6b_g {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M17.654 4.5h7.382v1.552a6.977 6.977 0 0 1-6.974 6.974h-.408zm17.141 13.258V12.51l-21.59 3.406v5.248l4.45-.702v2.999l-4.45.702v5.247l4.45-.701v5.068c0 11.002 9.959 10.726 15.943 8.47V35.48c-3.176 1.52-8.562 1.657-8.562-1.703v-6.233l9.759-1.54v-5.248l-9.76 1.54v-2.999z");
}

</style>
