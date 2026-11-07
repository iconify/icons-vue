<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/n/nd-3gubon.css';
import '../../css/t/tb_maib5c.css';
import '../../css/d/dz1ggsbih.css';
import '../../css/u/u8gkuv4uz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><circle class="nd-3gubon"/><path class="tb_maib5c"/><path class="dz1ggsbih"/><path class="u8gkuv4uz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:stopwatch-pause-line-duotone" /></template>
