<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ghrmtkbfr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:today-outline-sharp" /></template>
<style>
.ghrmtkbfr {
  fill: currentColor;
  d: path("M7.504 14.996q-.62-.619-.62-1.496t.62-1.496T9 11.384t1.496.62t.62 1.496t-.62 1.496t-1.496.62t-1.496-.62M4 21V5h3.385V2.77h1.077V5h7.154V2.77h1V5H20v16zm1-1h14v-9.384H5zM5 9.615h14V6H5zm0 0V6z");
}

</style>
