<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/p/pfn07zssj.css';
import '../../css/x/xw9d8bbop.css';
import '../../css/c/cp0l62b-f.css';
import '../../css/z/z8_kn595i.css';
import '../../css/f/fcg6i2y3h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="pfn07zssj"/><path class="wm-k xw9d8bbop"/><path class="cp0l62b-f wm-a"/><path class="wm-k z8_kn595i"/><path class="fcg6i2y3h wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:potted-plant-sketch" /></template>
