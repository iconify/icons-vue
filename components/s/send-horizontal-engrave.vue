<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/l/l01wgmbii.css';
import '../../css/e/e980yoblz.css';
import '../../css/u/uu_zhdcpe.css';
import '../../css/h/h0rhmfbpn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="l01wgmbii wm-k"/><path class="e980yoblz wm-shadow"/><path class="uu_zhdcpe wm-k"/><path class="h0rhmfbpn wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:send-horizontal-engrave" /></template>
