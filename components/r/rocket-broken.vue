<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/o/omvizacjo.css';
import '../../css/k/k6knkcfzc.css';
import '../../css/c/c-9ps4isn.css';
import '../../css/t/tangbccak.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="omvizacjo"/><path class="k6knkcfzc"/><path class="c-9ps4isn"/><path class="tangbccak"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:rocket-broken" /></template>
