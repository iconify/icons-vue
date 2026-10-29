<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/h/hqbh9vesp.css';
import '../../css/w/w1dkrwbfj.css';
import '../../css/o/ol-kpp5cg.css';
import '../../css/u/u-vfx8bll.css';
import '../../css/g/g3cuk7bic.css';
import '../../css/v/vxuqhab0r.css';
import '../../css/q/qr4ochb5c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="hqbh9vesp wm-k"/><path class="w1dkrwbfj wm-a"/><path class="ol-kpp5cg wm-s"/><path class="u-vfx8bll wm-shadow"/><path class="g3cuk7bic wm-k"/><path class="vxuqhab0r wm-a"/><path class="qr4ochb5c wm-s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:monitor-off-engrave" /></template>
