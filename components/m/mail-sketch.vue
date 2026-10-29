<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/j/jdkpgfdem.css';
import '../../css/h/h2b3rolij.css';
import '../../css/o/o-t2vm4xb.css';
import '../../css/p/pxnvek8pu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="jdkpgfdem"/><path class="h2b3rolij wm-a"/><path class="o-t2vm4xb wm-k"/><path class="pxnvek8pu wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:mail-sketch" /></template>
