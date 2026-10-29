<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/m/m4dq46b2l.css';
import '../../css/c/c40o4qbmy.css';
import '../../css/i/ihz715blo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="m4dq46b2l"/><path class="c40o4qbmy wm-shadow"/><path class="ihz715blo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:spider-web-engrave" /></template>
