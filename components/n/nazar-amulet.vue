<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tyt2l_voi.css';
import '../../css/y/yn6p1eb0k.css';
import '../../css/u/u5s7reayv.css';
import '../../css/c/c41e271zx.css';
import '../../css/c/cqchpb_dl.css';
import '../../css/h/hzhb0bcwn.css';
import '../../css/m/mal5nabbb.css';
import '../../css/x/x5fyvquan.css';
import '../../css/u/ukzwolvdp.css';
import '../../css/v/vzooosfab.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<circle class="tyt2l_voi"/><path class="yn6p1eb0k"/><circle class="u5s7reayv"/><circle class="c41e271zx"/><path class="cqchpb_dl"/><g class="hzhb0bcwn"><circle class="mal5nabbb"/><circle class="x5fyvquan"/><circle class="ukzwolvdp"/><circle class="vzooosfab"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:nazar-amulet" /></template>
