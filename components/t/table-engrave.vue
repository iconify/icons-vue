<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/u/uf2l6lbxy.css';
import '../../css/e/e_gp3jbds.css';
import '../../css/p/pp76qbckp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="uf2l6lbxy"/><path class="e_gp3jbds wm-shadow"/><path class="pp76qbckp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:table-engrave" /></template>
