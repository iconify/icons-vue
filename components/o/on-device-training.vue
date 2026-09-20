<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l152ncblj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:on-device-training" /></template>
<style>
.l152ncblj {
  fill: currentColor;
  d: path("M11.308 16.539v-.77h1.384v.77zm0-1.27v-.717q-.437-.256-.718-.651T10.308 13q0-.698.5-1.195q.502-.497 1.192-.497t1.191.497t.501 1.195q0 .506-.282.901t-.718.65v.718zm4.654.2l-.646-.633q.236-.425.364-.886q.128-.46.128-.945t-.128-.951t-.364-.89l.645-.633q.366.545.549 1.174q.182.63.182 1.296t-.182 1.29t-.548 1.178m-7.923 0q-.366-.545-.548-1.174q-.183-.63-.183-1.295q0-1.96 1.366-3.326T12 8.308v-.866l1.48 1.308L12 10.058v-.866q-1.585 0-2.696 1.116Q8.192 11.423 8.192 13q0 .487.128.95t.365.887zM6.616 22q-.667 0-1.141-.475T5 20.386V3.615q0-.666.475-1.14T6.615 2h10.77q.666 0 1.14.475T19 3.614v16.77q0 .666-.475 1.14t-1.14.475zM6 18.5h12v-13H6z");
}

</style>
