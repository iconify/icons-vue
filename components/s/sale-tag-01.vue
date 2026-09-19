<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/a/a07s13bxo.css';
import '../../css/q/qc1ru30_a.css';
import '../../css/s/sk8x0nbms.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="a07s13bxo"/><path class="qc1ru30_a"/><path class="sk8x0nbms"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:sale-tag-01" /></template>
