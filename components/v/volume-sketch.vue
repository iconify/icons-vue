<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/j/jlc_yjb6o.css';
import '../../css/i/i09ron92k.css';
import '../../css/x/xoi8mrm8l.css';
import '../../css/d/dydwk4bgd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="jlc_yjb6o"/><path class="i09ron92k wm-a"/><path class="wm-k xoi8mrm8l"/><path class="dydwk4bgd wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:volume-sketch" /></template>
