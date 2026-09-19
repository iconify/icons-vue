<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/v/v10bhlb1p.css';
import '../../css/f/f9o0vpbpo.css';
import '../../css/k/kmc74e6rd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="v10bhlb1p"/><path class="f9o0vpbpo"/><path class="kmc74e6rd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:remove-pi" /></template>
