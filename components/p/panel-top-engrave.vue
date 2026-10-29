<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/u/u9qz1eb7n.css';
import '../../css/h/huw3ambik.css';
import '../../css/o/og437mbap.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="u9qz1eb7n"/><path class="huw3ambik wm-shadow"/><path class="og437mbap"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:panel-top-engrave" /></template>
