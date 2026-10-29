<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/q/qhv7smboy.css';
import '../../css/g/ghuygmbqm.css';
import '../../css/t/tua1e724v.css';
import '../../css/l/lqpi8na-k.css';
import '../../css/j/jm-o6kx0w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="qhv7smboy wm-k"/><path class="ghuygmbqm wm-a"/><path class="tua1e724v wm-shadow"/><path class="lqpi8na-k wm-k"/><path class="jm-o6kx0w wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:pencil-engrave" /></template>
