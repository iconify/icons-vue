<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/m/m2o0--btk.css';
import '../../css/m/mi2rz7bua.css';
import '../../css/o/ol3yr344y.css';
import '../../css/b/bk04fhbuy.css';
import '../../css/q/q42xo2b2p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="m2o0--btk wm-k"/><path class="mi2rz7bua wm-a"/><path class="ol3yr344y wm-shadow"/><path class="bk04fhbuy wm-k"/><path class="q42xo2b2p wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:sun-dim-engrave" /></template>
