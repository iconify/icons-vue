<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/l/lg4hmt8ek.css';
import '../../css/t/t266g0bnv.css';
import '../../css/m/mszfd9biq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="lg4hmt8ek"/><path class="t266g0bnv"/><path class="mszfd9biq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:map-linear" /></template>
