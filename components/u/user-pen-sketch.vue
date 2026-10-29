<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/g/gn6miabce.css';
import '../../css/t/t7-3-qbad.css';
import '../../css/i/igk2wisce.css';
import '../../css/y/ysiww79nn.css';
import '../../css/i/i9tasabhu.css';
import '../../css/n/n8h22mt3n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="gn6miabce wm-k"/><path class="t7-3-qbad wm-k"/><path class="igk2wisce wm-k"/><path class="wm-s ysiww79nn"/><path class="i9tasabhu wm-s"/><path class="n8h22mt3n wm-s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:user-pen-sketch" /></template>
