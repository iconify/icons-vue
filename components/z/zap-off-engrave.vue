<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/c/ccyqkhomb.css';
import '../../css/i/i64imcqzx.css';
import '../../css/m/m9qb4nitn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="ccyqkhomb"/><path class="i64imcqzx wm-shadow"/><path class="m9qb4nitn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:zap-off-engrave" /></template>
