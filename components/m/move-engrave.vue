<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/k/kvce4pl-l.css';
import '../../css/x/xqh9rrg0g.css';
import '../../css/t/txsvwdb1u.css';
import '../../css/u/u1of9ltii.css';
import '../../css/n/ngurz8bhm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="kvce4pl-l wm-k"/><path class="wm-a xqh9rrg0g"/><path class="txsvwdb1u wm-shadow"/><path class="u1of9ltii wm-k"/><path class="ngurz8bhm wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:move-engrave" /></template>
