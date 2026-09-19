<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/p/pvpjlb97s.css';
import '../../css/x/xrdxaeb5q.css';
import '../../css/j/j7k2ckmjp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="pvpjlb97s"/><path class="xrdxaeb5q"/><path class="j7k2ckmjp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:save-money-euro" /></template>
