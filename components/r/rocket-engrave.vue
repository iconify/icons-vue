<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/m/mmpilc2kg.css';
import '../../css/g/g4d5lbhnu.css';
import '../../css/s/slf43thyj.css';
import '../../css/b/bunwpimed.css';
import '../../css/g/g71l8mfcw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="mmpilc2kg wm-k"/><path class="g4d5lbhnu wm-a"/><path class="slf43thyj wm-shadow"/><path class="bunwpimed wm-k"/><path class="g71l8mfcw wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:rocket-engrave" /></template>
