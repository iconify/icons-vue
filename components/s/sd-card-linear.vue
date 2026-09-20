<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/o/orqtdgb5k.css';
import '../../css/p/pmwvkubtc.css';
import '../../css/g/gkiwa1bxg.css';
import '../../css/r/r02hdib4f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="orqtdgb5k"/><path class="pmwvkubtc"/><path class="gkiwa1bxg"/><path class="r02hdib4f"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:sd-card-linear" /></template>
