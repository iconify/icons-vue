<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/o/olvz54bxq.css';
import '../../css/z/zslfi4b0o.css';
import '../../css/p/pbwadabrx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="olvz54bxq"/><path class="zslfi4b0o"/><path class="pbwadabrx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:square-arrow-up-right-02" /></template>
