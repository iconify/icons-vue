<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/w/w4-05cc6z.css';
import '../../css/s/s-ypsc2gv.css';
import '../../css/l/leur-h8bg.css';
import '../../css/d/dlgm9h3nj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="w4-05cc6z"/><path class="s-ypsc2gv"/><path class="leur-h8bg"/><path class="dlgm9h3nj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:palette-round-linear" /></template>
