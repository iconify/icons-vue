<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/x/xrry15w0o.css';
import '../../css/y/yc1eq-awn.css';
import '../../css/w/wk0dhccfa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="xrry15w0o"/><path class="yc1eq-awn"/><path class="wk0dhccfa"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:panel-left-open-linear" /></template>
