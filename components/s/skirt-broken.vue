<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/d/dm2oz9bnr.css';
import '../../css/y/yv44zccgq.css';
import '../../css/t/t-og4eyuq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="dm2oz9bnr"/><path class="yv44zccgq"/><path class="t-og4eyuq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:skirt-broken" /></template>
