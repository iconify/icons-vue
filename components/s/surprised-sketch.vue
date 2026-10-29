<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/q/qb-mlqbns.css';
import '../../css/e/esc57vs2e.css';
import '../../css/r/r40fi4qti.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="qb-mlqbns"/><path class="esc57vs2e wm-k"/><path class="r40fi4qti wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:surprised-sketch" /></template>
