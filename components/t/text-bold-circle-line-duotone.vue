<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/c/cxzlycbfj.css';
import '../../css/r/r6ybk4brv.css';
import '../../css/r/rwmcjfboi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="cxzlycbfj"/><path class="r6ybk4brv"/><path class="rwmcjfboi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:text-bold-circle-line-duotone" /></template>
