<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/w/wvopw9ncy.css';
import '../../css/t/two_v_bki.css';
import '../../css/q/q1-hjfupd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="wvopw9ncy"/><path class="two_v_bki wm-shadow"/><path class="q1-hjfupd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:strikethrough-engrave" /></template>
