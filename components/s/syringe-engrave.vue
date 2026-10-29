<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/v/vu5gm21iq.css';
import '../../css/z/zpgfllj7j.css';
import '../../css/c/ca-kc0lhr.css';
import '../../css/n/ncllzy-2b.css';
import '../../css/o/o1d41pbvf.css';
import '../../css/i/igb3ajb3y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="vu5gm21iq wm-k"/><path class="wm-a zpgfllj7j"/><path class="ca-kc0lhr wm-shadow"/><path class="ncllzy-2b wm-k"/><path class="o1d41pbvf wm-a"/><path class="igb3ajb3y wm-k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:syringe-engrave" /></template>
