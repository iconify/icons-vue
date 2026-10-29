<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/j/jt065lb1t.css';
import '../../css/k/kz9qlpk6s.css';
import '../../css/q/qit5teboe.css';
import '../../css/s/sfp-qh-hh.css';
import '../../css/x/x74picb7l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="jt065lb1t wm-k"/><path class="kz9qlpk6s wm-s"/><path class="qit5teboe wm-shadow"/><path class="sfp-qh-hh wm-k"/><path class="wm-s x74picb7l"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:moon-star-engrave" /></template>
