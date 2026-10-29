<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/c/co6ufk7zc.css';
import '../../css/r/rgpf1zbjs.css';
import '../../css/y/yo87urbrl.css';
import '../../css/d/d5_gd2mux.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="co6ufk7zc"/><path class="rgpf1zbjs wm-shadow"/><path class="yo87urbrl"/><path class="d5_gd2mux"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:martini-engrave" /></template>
