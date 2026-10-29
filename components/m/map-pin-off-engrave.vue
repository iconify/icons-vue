<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/b/b574m1b9n.css';
import '../../css/h/hjub0vp3e.css';
import '../../css/o/ol-kpp5cg.css';
import '../../css/q/qt692bbex.css';
import '../../css/u/udqu4n_ci.css';
import '../../css/e/e39p62u0b.css';
import '../../css/q/qr4ochb5c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="b574m1b9n wm-k"/><path class="hjub0vp3e wm-a"/><path class="ol-kpp5cg wm-s"/><path class="qt692bbex wm-shadow"/><path class="udqu4n_ci wm-k"/><path class="e39p62u0b wm-a"/><path class="qr4ochb5c wm-s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:map-pin-off-engrave" /></template>
