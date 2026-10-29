<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/r/re6n26bxt.css';
import '../../css/n/n0om6cbya.css';
import '../../css/d/d5s3tzbfe.css';
import '../../css/k/kcag22w9s.css';
import '../../css/f/f98ia0txa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="re6n26bxt wm-k"/><path class="n0om6cbya wm-a"/><path class="d5s3tzbfe wm-shadow"/><path class="kcag22w9s wm-k"/><path class="f98ia0txa wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:qr-code-engrave" /></template>
