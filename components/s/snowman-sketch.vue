<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/t/t7u_uqbzp.css';
import '../../css/q/q4dv6qklc.css';
import '../../css/u/usozbobia.css';
import '../../css/h/hr6436luy.css';
import '../../css/s/snhr-fvoo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="t7u_uqbzp wm-k"/><path class="q4dv6qklc wm-a"/><path class="usozbobia wm-k"/><path class="hr6436luy wm-a"/><path class="snhr-fvoo wm-s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:snowman-sketch" /></template>
