<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ycmeor3zs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:print-landscape-long-sharp" /></template>
<style>
.ycmeor3zs {
  fill: currentColor;
  d: path("M14.23 5h1.924v.923h3.165l.681.85l-2.217 6.593H3.523l-.546-.812l2.294-6.631H7.77V5h1.923v.923h4.539zM5 14.385h13.648L20 10.475V18H5z");
}

</style>
