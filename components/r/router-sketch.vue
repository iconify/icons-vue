<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/d/dzby_kbty.css';
import '../../css/f/f2v3xdrlx.css';
import '../../css/s/s2a91vbxp.css';
import '../../css/s/sds2cyb9y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="dzby_kbty"/><path class="f2v3xdrlx wm-a"/><path class="s2a91vbxp wm-k"/><path class="sds2cyb9y wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:router-sketch" /></template>
