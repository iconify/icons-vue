<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/e/ekrd5abyk.css';
import '../../css/i/ihafutcib.css';
import '../../css/g/gp_s3dbvu.css';
import '../../css/t/t7qux-1ws.css';
import '../../css/y/yn2qumbxf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="ekrd5abyk"/><path class="ihafutcib wm-k"/><path class="gp_s3dbvu wm-a"/><path class="t7qux-1ws wm-k"/><path class="wm-a yn2qumbxf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:martini-sketch" /></template>
