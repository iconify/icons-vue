<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/o/o87xgabpe.css';
import '../../css/y/y8hrvjbyx.css';
import '../../css/v/vu5-wubns.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="o87xgabpe"/><path class="y8hrvjbyx"/><path class="vu5-wubns"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:medal-star-square-broken" /></template>
