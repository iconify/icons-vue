<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/u/uoxth4t8w.css';
import '../../css/o/ogeuw0bqm.css';
import '../../css/a/ax1-ht12b.css';
import '../../css/n/nnixupllg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="uoxth4t8w"/><path class="ogeuw0bqm wm-shadow"/><path class="ax1-ht12b"/><path class="nnixupllg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:tennis-engrave" /></template>
