<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/g/ggvf3nb4s.css';
import '../../css/c/cw0dg-bgf.css';
import '../../css/e/erekrcbav.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="ggvf3nb4s"/><path class="cw0dg-bgf"/><path class="erekrcbav"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:smartphone-update-broken" /></template>
