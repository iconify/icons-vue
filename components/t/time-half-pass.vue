<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/a/avo-_rbdv.css';
import '../../css/v/vvm_1sbqe.css';
import '../../css/z/znqljt_fj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="avo-_rbdv"/><path class="vvm_1sbqe"/><path class="znqljt_fj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:time-half-pass" /></template>
