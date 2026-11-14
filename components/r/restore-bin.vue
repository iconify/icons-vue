<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/x/x75rvijcw.css';
import '../../css/k/kw_evg14q.css';
import '../../css/d/d3mtwbcfv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="x75rvijcw"/><path class="kw_evg14q"/><path class="d3mtwbcfv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:restore-bin" /></template>
