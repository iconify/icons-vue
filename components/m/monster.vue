<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/c/c_kplcszs.css';
import '../../css/v/vfymv3unk.css';
import '../../css/q/qsz9j-v2y.css';
import '../../css/t/td1hxgbap.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="c_kplcszs"/><path class="vfymv3unk"/><path class="qsz9j-v2y"/><path class="td1hxgbap"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:monster" /></template>
