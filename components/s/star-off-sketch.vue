<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/m/mmqlpiqfo.css';
import '../../css/m/memzlwbyy.css';
import '../../css/b/bvwl46b5l.css';
import '../../css/w/wx0gwswyg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="mmqlpiqfo wm-k"/><path class="memzlwbyy wm-s"/><path class="bvwl46b5l wm-k"/><path class="wm-s wx0gwswyg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:star-off-sketch" /></template>
