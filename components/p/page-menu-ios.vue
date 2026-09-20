<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jc8p-3bgw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:page-menu-ios" /></template>
<style>
.jc8p-3bgw {
  fill: currentColor;
  d: path("M4 20v-1h10.366v1zm0-3.384v-1h16v1zm1.616-3.385q-.691 0-1.153-.463T4 11.616v-6q0-.691.463-1.153T5.616 4h12.769q.69 0 1.153.463T20 5.616v6q0 .69-.462 1.152t-1.153.463z");
}

</style>
