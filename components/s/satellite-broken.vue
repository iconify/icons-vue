<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/d/dqvkli3td.css';
import '../../css/t/tev0_7rwp.css';
import '../../css/w/wawugdb_n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="dqvkli3td"/><path class="tev0_7rwp"/><path class="wawugdb_n"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:satellite-broken" /></template>
