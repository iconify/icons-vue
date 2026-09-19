<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/s/s46c2220x.css';
import '../../css/w/wr28_ubwm.css';
import '../../css/b/be91r0mqb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="s46c2220x"/><path class="wr28_ubwm"/><path class="be91r0mqb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:square-lock-add-01" /></template>
