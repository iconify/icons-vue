<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/q/qgu7_ebsb.css';
import '../../css/k/kva043bzk.css';
import '../../css/t/t26d7g3rg.css';
import '../../css/p/pf1ifwbeb.css';
import '../../css/y/y-9fctbqs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="qgu7_ebsb"/><path class="kva043bzk"/><path class="t26d7g3rg"/><path class="pf1ifwbeb"/><path class="y-9fctbqs"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:webcam-linear" /></template>
