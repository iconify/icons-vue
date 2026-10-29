<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/a/axctq6bkz.css';
import '../../css/h/hui8iubvv.css';
import '../../css/z/zqvy67bxh.css';
import '../../css/l/louzr2q0b.css';
import '../../css/w/wox8e5-la.css';
import '../../css/i/iqev0abij.css';
import '../../css/n/nl8tjs5bg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="axctq6bkz wm-k"/><path class="hui8iubvv wm-a"/><path class="wm-shadow zqvy67bxh"/><path class="louzr2q0b wm-k"/><path class="wm-a wox8e5-la"/><path class="iqev0abij wm-k"/><path class="nl8tjs5bg wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:swap-engrave" /></template>
