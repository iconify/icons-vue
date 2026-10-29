<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/p/pjytr7bkn.css';
import '../../css/h/h8vo_l87w.css';
import '../../css/x/x-5rr3xtm.css';
import '../../css/t/tx2v7znqn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="pjytr7bkn"/><path class="h8vo_l87w wm-a"/><path class="wm-k x-5rr3xtm"/><path class="tx2v7znqn wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:sd-card-sketch" /></template>
