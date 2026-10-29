<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/i/ij_oxib5j.css';
import '../../css/r/r0r9_sije.css';
import '../../css/l/l6swvrbfj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="ij_oxib5j"/><path class="r0r9_sije wm-shadow"/><path class="l6swvrbfj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:play-engrave" /></template>
