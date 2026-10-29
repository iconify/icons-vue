<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/e/eldtd1r2s.css';
import '../../css/b/bmf49mbpn.css';
import '../../css/x/xnuytgkwb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="eldtd1r2s"/><path class="bmf49mbpn wm-shadow"/><path class="xnuytgkwb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:virus-engrave" /></template>
