<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/g/gnci-5bia.css';
import '../../css/y/yc6f2ibtn.css';
import '../../css/s/swrq_pkri.css';
import '../../css/k/k8lhefb8t.css';
import '../../css/i/iosp0x2su.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="gnci-5bia"/><path class="wm-k yc6f2ibtn"/><path class="swrq_pkri wm-a"/><path class="k8lhefb8t wm-k"/><path class="iosp0x2su wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:scroll-text-sketch" /></template>
