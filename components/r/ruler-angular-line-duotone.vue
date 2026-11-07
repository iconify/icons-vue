<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/s/sb0q3diim.css';
import '../../css/t/t3i0929hw.css';
import '../../css/n/noowh5fsj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="sb0q3diim"/><path class="t3i0929hw"/><path class="noowh5fsj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:ruler-angular-line-duotone" /></template>
