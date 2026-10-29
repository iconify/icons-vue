<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/w/wen-xabgo.css';
import '../../css/a/a2dvtxbze.css';
import '../../css/l/lxfcxwbpl.css';
import '../../css/u/u_zk5lblv.css';
import '../../css/h/hvtijj65u.css';
import '../../css/q/qfb54wbgr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="wen-xabgo wm-k"/><path class="a2dvtxbze wm-a"/><path class="lxfcxwbpl wm-shadow"/><path class="u_zk5lblv wm-k"/><path class="hvtijj65u wm-a"/><path class="qfb54wbgr wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:salad-engrave" /></template>
