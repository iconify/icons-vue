<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m3p4rt7lp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:tools-power-drill-sharp" /></template>
<style>
.m3p4rt7lp {
  fill: currentColor;
  d: path("M6.5 9.5h5.385v-.885H6.5zm0-2.116h5.385V6.5H6.5zm9.27 2.808V5.808h1.422l.808.808V7.5h2.192v1H18v.885l-.808.807zm-8.578 3.385v-1.77h-.807q-1.238 0-2.12-.88t-.88-2.12V7.193q0-1.237.88-2.118t2.12-.882H15v7.616h-3.808v1.769zm-1.615 4.23v-3.46h7.23v3.46z");
}

</style>
