<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/z/zf6m_rg7v.css';
import '../../css/d/dv86dk8ai.css';
import '../../css/t/t3tivrbho.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="zf6m_rg7v"/><path class="dv86dk8ai"/><path class="t3tivrbho"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:tag-price-broken" /></template>
