<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/q/qc670fb8v.css';
import '../../css/h/hausojmrr.css';
import '../../css/c/cdb9mdikz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="qc670fb8v wm-a"/><path class="hausojmrr wm-k"/><path class="cdb9mdikz wm-k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:panel-right-sketch" /></template>
