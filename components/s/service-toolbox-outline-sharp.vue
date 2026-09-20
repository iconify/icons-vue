<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k7bjfdbkq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:service-toolbox-outline-sharp" /></template>
<style>
.k7bjfdbkq {
  fill: currentColor;
  d: path("M8.192 7V4.846h7.616V7h2.513L21 13.066V19H3v-5.934L5.679 7zm1 0h5.616V5.846H9.192zM7.5 12.692v-1h1v1h7v-1h1v1h3.246L17.7 8H6.3l-2.046 4.692zm0 1H4V18h16v-4.308h-3.5v1h-1v-1h-7v1h-1zm4.5 0");
}

</style>
