<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/z/zqnwjnvva.css';
import '../../css/s/s1farrbte.css';
import '../../css/l/ltkx6wbhl.css';
import '../../css/w/wrbf2zb1l.css';
import '../../css/x/xgrg7usag.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="wm-k zqnwjnvva"/><path class="s1farrbte wm-a"/><path class="ltkx6wbhl wm-shadow"/><path class="wm-k wrbf2zb1l"/><path class="wm-a xgrg7usag"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:rotate-cw-engrave" /></template>
