<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/y/y3ujnnbol.css';
import '../../css/d/d18ai5beg.css';
import '../../css/o/ojr5lccvy.css';
import '../../css/u/urhp2vbzd.css';
import '../../css/w/wj3l2jslf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="y3ujnnbol"/><path class="d18ai5beg wm-k"/><path class="ojr5lccvy wm-a"/><path class="urhp2vbzd wm-k"/><path class="wj3l2jslf wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:mandarin-orange-sketch" /></template>
