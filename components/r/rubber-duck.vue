<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/g/g33dr_b1f.css';
import '../../css/n/n2ckldr-l.css';
import '../../css/d/dlvig_bmn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="g33dr_b1f"/><path class="n2ckldr-l"/><path class="dlvig_bmn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:rubber-duck" /></template>
