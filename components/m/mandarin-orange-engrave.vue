<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/z/z2nb1fbmj.css';
import '../../css/q/q-m_x2bgm.css';
import '../../css/g/grk8hzbpa.css';
import '../../css/f/f24-gqbst.css';
import '../../css/r/r-nr70vpq.css';
import '../../css/m/m31z5l3iz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="wm-k z2nb1fbmj"/><path class="q-m_x2bgm wm-a"/><path class="grk8hzbpa wm-shadow"/><path class="f24-gqbst wm-k"/><path class="r-nr70vpq wm-a"/><path class="m31z5l3iz wm-k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:mandarin-orange-engrave" /></template>
