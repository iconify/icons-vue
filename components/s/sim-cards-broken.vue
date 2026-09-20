<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/h/hyhh_hbgv.css';
import '../../css/s/sszxh7b9e.css';
import '../../css/o/o431y0bll.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="hyhh_hbgv"/><path class="sszxh7b9e"/><path class="o431y0bll"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:sim-cards-broken" /></template>
