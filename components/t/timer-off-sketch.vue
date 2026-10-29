<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/k/kwpmtnzgp.css';
import '../../css/r/rn0af2bkg.css';
import '../../css/q/q7nzdkbef.css';
import '../../css/q/qm5omdbnp.css';
import '../../css/z/zj1vorbtd.css';
import '../../css/x/xmdw_emec.css';
import '../../css/x/xe2yj3rul.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="kwpmtnzgp"/><path class="rn0af2bkg wm-k"/><path class="q7nzdkbef wm-a"/><path class="qm5omdbnp wm-s"/><path class="wm-k zj1vorbtd"/><path class="wm-a xmdw_emec"/><path class="wm-s xe2yj3rul"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:timer-off-sketch" /></template>
