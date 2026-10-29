<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/d/dg5g5cnba.css';
import '../../css/p/p_yvxebuk.css';
import '../../css/b/bhq6bo-ou.css';
import '../../css/x/xm7lx-c5p.css';
import '../../css/q/qj_ikebkq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="dg5g5cnba wm-k"/><path class="p_yvxebuk wm-k"/><path class="bhq6bo-ou wm-k"/><path class="wm-k xm7lx-c5p"/><path class="qj_ikebkq wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:north-star-sketch" /></template>
