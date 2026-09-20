<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fmsr3kb1i.css';
import '../../css/b/brzn_0bpr.css';
import '../../css/n/n2p5-ed3s.css';
import '../../css/m/mt5816bop.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="fmsr3kb1i"/><g class="brzn_0bpr"><path class="n2p5-ed3s"/><path class="mt5816bop"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:power-on-off-symbol" /></template>
