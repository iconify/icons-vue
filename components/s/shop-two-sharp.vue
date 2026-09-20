<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qv59o5ban"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:shop-two-sharp" /></template>
<style>
.qv59o5ban {
  fill: currentColor;
  d: path("m12 14.27l4.077-2.578L12 9.116zM2 20.191V9.423h1v9.77h15.5v1zm3-3v-11h5.308V3h6.384v3.192H22v11zm6.308-11h4.384V4h-4.384z");
}

</style>
