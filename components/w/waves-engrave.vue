<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/g/gs4rmbc_b.css';
import '../../css/u/u8506e-ir.css';
import '../../css/f/fvgsbq1kt.css';
import '../../css/g/gwq6sk28r.css';
import '../../css/k/kgbn2cc9v.css';
import '../../css/h/h9urc9bth.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="gs4rmbc_b wm-k"/><path class="u8506e-ir wm-a"/><path class="fvgsbq1kt wm-shadow"/><path class="gwq6sk28r wm-a"/><path class="kgbn2cc9v wm-k"/><path class="h9urc9bth wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:waves-engrave" /></template>
