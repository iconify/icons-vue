<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/a/amm3vz60d.css';
import '../../css/z/z7szs-qkm.css';
import '../../css/w/w5r3v6b7x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="amm3vz60d"/><path class="z7szs-qkm"/><path class="w5r3v6b7x"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:tif-format" /></template>
