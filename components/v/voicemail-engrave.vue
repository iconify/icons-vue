<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/p/pbbswkb8p.css';
import '../../css/t/totmvqulo.css';
import '../../css/a/apbxdlbgs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="pbbswkb8p"/><path class="totmvqulo wm-shadow"/><path class="apbxdlbgs"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:voicemail-engrave" /></template>
