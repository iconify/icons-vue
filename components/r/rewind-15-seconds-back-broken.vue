<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/m/mah77fbvh.css';
import '../../css/t/tgcis5bxj.css';
import '../../css/y/yvh9lfbdn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="mah77fbvh"/><path class="tgcis5bxj"/><path class="yvh9lfbdn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:rewind-15-seconds-back-broken" /></template>
