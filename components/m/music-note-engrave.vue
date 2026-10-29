<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/r/rstupirhr.css';
import '../../css/m/mfuq2zbnj.css';
import '../../css/g/gle5llb7u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="rstupirhr"/><path class="mfuq2zbnj wm-shadow"/><path class="gle5llb7u"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:music-note-engrave" /></template>
