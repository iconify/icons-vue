<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/k/kdw-60bcj.css';
import '../../css/q/qgw9asb_i.css';
import '../../css/i/i0zlx3npb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="kdw-60bcj"/><path class="qgw9asb_i"/><path class="i0zlx3npb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:text-subscript" /></template>
