<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/y/y12b4kt4p.css';
import '../../css/j/jug4rg7qe.css';
import '../../css/p/pcxdo28jt.css';
import '../../css/i/iz8w4e7ux.css';
import '../../css/f/folfl_fvi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="wm-k y12b4kt4p"/><path class="jug4rg7qe wm-shadow"/><path class="pcxdo28jt wm-k"/><path class="iz8w4e7ux wm-k"/><path class="folfl_fvi wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:snow-globe-engrave" /></template>
