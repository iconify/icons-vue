<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/k/knwu_bb7f.css';
import '../../css/s/scfy6rb1m.css';
import '../../css/m/m-zvanb9g.css';
import '../../css/l/l9lv5_bcf.css';
import '../../css/x/x8izv9k1w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="knwu_bb7f wm-k"/><path class="scfy6rb1m wm-a"/><path class="m-zvanb9g wm-shadow"/><path class="l9lv5_bcf wm-k"/><path class="wm-a x8izv9k1w"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:scan-barcode-engrave" /></template>
