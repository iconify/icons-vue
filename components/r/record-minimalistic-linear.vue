<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/d/d71s9bpxk.css';
import '../../css/i/i55b91czr.css';
import '../../css/o/oh-a85bpt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="d71s9bpxk"/><path class="i55b91czr"/><path class="oh-a85bpt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:record-minimalistic-linear" /></template>
