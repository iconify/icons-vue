<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/l/lc4s8kbon.css';
import '../../css/g/gybzzbn-v.css';
import '../../css/q/q0a-0wbuy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="lc4s8kbon"/><path class="gybzzbn-v"/><path class="q0a-0wbuy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:mask-love" /></template>
