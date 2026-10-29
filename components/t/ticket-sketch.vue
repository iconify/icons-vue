<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/r/rbpy15bdk.css';
import '../../css/u/uvsyy_17f.css';
import '../../css/q/qc8g0bcwg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="rbpy15bdk"/><path class="uvsyy_17f wm-k"/><path class="qc8g0bcwg wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:ticket-sketch" /></template>
