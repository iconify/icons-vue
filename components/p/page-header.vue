<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f7ptiwbvr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:page-header" /></template>
<style>
.f7ptiwbvr {
  fill: currentColor;
  d: path("M4 5V4h16v1zm14.385 2.385q.69 0 1.153.462T20 9v9.385q0 .69-.462 1.153T18.384 20H5.616q-.691 0-1.153-.462T4 18.384V9q0-.69.463-1.153t1.153-.463z");
}

</style>
