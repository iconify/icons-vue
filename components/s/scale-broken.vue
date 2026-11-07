<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/z/zh_u0iaqv.css';
import '../../css/h/hwifnpb2v.css';
import '../../css/r/rlv2bxh-p.css';
import '../../css/w/wvqgt30sr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="zh_u0iaqv"/><path class="hwifnpb2v"/><path class="rlv2bxh-p"/><path class="wvqgt30sr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:scale-broken" /></template>
