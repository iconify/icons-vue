<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/m/mu6gvu5iy.css';
import '../../css/k/k-hxx4vnx.css';
import '../../css/d/dt7ysyxnd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="mu6gvu5iy"/><path class="k-hxx4vnx"/><path class="dt7ysyxnd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:mobile-security" /></template>
