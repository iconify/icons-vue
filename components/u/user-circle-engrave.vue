<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/f/f4abdvb7l.css';
import '../../css/i/i980sbb1t.css';
import '../../css/y/yw4fz_b6b.css';
import '../../css/y/yd398tbty.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="f4abdvb7l"/><path class="i980sbb1t wm-shadow"/><path class="yw4fz_b6b"/><path class="yd398tbty"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:user-circle-engrave" /></template>
