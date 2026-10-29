<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/q/qj7tvf8mc.css';
import '../../css/w/w159qr-wq.css';
import '../../css/c/csa53darn.css';
import '../../css/v/vywh8ob7f.css';
import '../../css/l/l8_xk16co.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="qj7tvf8mc"/><path class="w159qr-wq wm-k"/><path class="csa53darn wm-a"/><path class="vywh8ob7f wm-k"/><path class="l8_xk16co wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:message-circle-question-sketch" /></template>
