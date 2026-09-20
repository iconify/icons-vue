<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tifzeygbw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:on-device-training-sharp" /></template>
<style>
.tifzeygbw {
  fill: currentColor;
  d: path("M11.308 16.539v-.77h1.384v.77zm0-1.27v-.717q-.437-.256-.718-.651T10.308 13q0-.69.5-1.191q.502-.501 1.192-.501t1.191.5q.501.502.501 1.192q0 .506-.282.901t-.718.651v.717zm4.654.2l-.646-.633q.236-.425.364-.89t.128-.946t-.128-.946t-.364-.89l.645-.633q.366.554.549 1.179q.182.625.182 1.29t-.182 1.29t-.548 1.18m-7.923 0q-.366-.554-.548-1.18q-.183-.624-.183-1.29q0-1.96 1.366-3.326T12 8.308v-.866l1.48 1.308L12 10.058v-.866q-1.585 0-2.696 1.112T8.192 13q0 .48.128.946t.365.89zM5 22V2h14v20zm1-3.5h12v-13H6z");
}

</style>
