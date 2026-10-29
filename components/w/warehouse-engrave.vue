<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/c/cgswrs-9o.css';
import '../../css/q/qfum51-7d.css';
import '../../css/r/r-n_5ichr.css';
import '../../css/w/wmk_i8bat.css';
import '../../css/g/g3_i1_bjs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="cgswrs-9o wm-k"/><path class="qfum51-7d wm-a"/><path class="r-n_5ichr wm-shadow"/><path class="wm-k wmk_i8bat"/><path class="g3_i1_bjs wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:warehouse-engrave" /></template>
