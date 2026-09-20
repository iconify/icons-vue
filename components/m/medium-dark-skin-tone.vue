<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<linearGradient id="ssvg-id-medium-dark-skin-tonea" x1="64" x2="64" y1="4.333" y2="123.89" gradientUnits="userSpaceOnUse"><stop offset="0" class="ds1-pabkj"/><stop offset=".427" class="ft96n1eul"/><stop offset=".784" class="ahmjdbcih"/><stop offset="1" class="r2g_ajb0y"/></linearGradient><path fill="url(#ssvg-id-medium-dark-skin-tonea)" class="bwf9m2bjt"/><linearGradient id="ssvg-id-medium-dark-skin-toneb" x1="106" x2="106" y1="305.27" y2="305.27" gradientUnits="userSpaceOnUse"><stop offset="0" class="r2g_ajb0y"/><stop offset=".216" class="ahmjdbcih"/><stop offset=".573" class="ft96n1eul"/><stop offset="1" class="ds1-pabkj"/></linearGradient>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noto:medium-dark-skin-tone" /></template>
<style>
.ahmjdbcih {
  stop-color: var(--svg-color--97603d, #97603D);
}

.bwf9m2bjt {
  d: path("M4 4h120v120H4z");
}

.ds1-pabkj {
  stop-color: var(--svg-color--a56c43, #A56C43);
}

.ft96n1eul {
  stop-color: var(--svg-color--a26941, #A26941);
}

.r2g_ajb0y {
  stop-color: var(--svg-color--8d5738, #8D5738);
}

</style>
