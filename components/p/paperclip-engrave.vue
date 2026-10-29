<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/g/gxbk2tj2j.css';
import '../../css/r/ral12u3xi.css';
import '../../css/n/ns9l4jexk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="gxbk2tj2j"/><path class="ral12u3xi wm-shadow"/><path class="ns9l4jexk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:paperclip-engrave" /></template>
