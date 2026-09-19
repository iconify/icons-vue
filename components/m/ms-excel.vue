<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qfttfe_2y.css';
import '../../css/x/xwqlguw3x.css';
import '../../css/p/pn1ylfbdq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<g class="qfttfe_2y"><path class="xwqlguw3x"/><path class="pn1ylfbdq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="catppuccin:ms-excel" /></template>
