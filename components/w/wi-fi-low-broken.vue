<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/z/zj2p4py0y.css';
import '../../css/p/pn5tqtb4p.css';
import '../../css/i/iejxo-b0t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="zj2p4py0y"/><path class="pn5tqtb4p"/><path class="iejxo-b0t"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:wi-fi-low-broken" /></template>
