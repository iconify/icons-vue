<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/v/vzu_nabrz.css';
import '../../css/t/ttwf-zbzb.css';
import '../../css/l/lzc_04b6m.css';
import '../../css/o/on-fg_sbj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="vzu_nabrz"/><path class="ttwf-zbzb wm-a"/><path class="lzc_04b6m wm-k"/><path class="on-fg_sbj wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:search-x-sketch" /></template>
