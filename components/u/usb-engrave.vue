<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/g/g4rq9cb4b.css';
import '../../css/h/hiqgl-xto.css';
import '../../css/i/ialz71b-c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="g4rq9cb4b"/><path class="hiqgl-xto wm-shadow"/><path class="ialz71b-c"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:usb-engrave" /></template>
