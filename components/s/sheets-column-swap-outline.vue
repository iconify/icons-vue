<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u40gf4bae"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:sheets-column-swap-outline" /></template>
<style>
.u40gf4bae {
  fill: currentColor;
  d: path("M5 9.135V4h6.404v5.135zm1-1h4.404V5H6zM12.577 20v-8.884H19V20zm1-1H18v-2.942h-4.423zm0-3.942H18v-2.942h-4.423zm1.173-5.904v-1h2.537L14.462 5.29l.707-.714L18 7.447V4.865h1v4.288zm-5.925 7.538L6 13.83v2.575H5v-4.288h4.25v1H6.708l2.83 2.869z");
}

</style>
