<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/d/djiqt-b-p.css';
import '../../css/v/vfmfabckk.css';
import '../../css/n/nrf4-abjf.css';
import '../../css/e/emha3wbqe.css';
import '../../css/f/f5cf9ixua.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="djiqt-b-p wm-k"/><path class="vfmfabckk wm-s"/><path class="nrf4-abjf wm-shadow"/><path class="emha3wbqe wm-k"/><path class="f5cf9ixua wm-s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:user-check-engrave" /></template>
