<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/t/td81zzyxq.css';
import '../../css/i/i9m89s9zq.css';
import '../../css/z/zxp0ecb1d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="td81zzyxq"/><path class="i9m89s9zq"/><path class="zxp0ecb1d"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:map-pin-search" /></template>
