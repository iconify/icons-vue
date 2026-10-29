<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s9nmekbvz.css';
import '../../css/q/qmbe2g6no.css';
import '../../css/g/g6c2-s7sy.css';
import '../../css/c/cf3uzcrzx.css';
import '../../css/g/gsn30ubhe.css';
import '../../css/u/uc0yabbtt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s9nmekbvz"><path class="qmbe2g6no wm-deco"/><path class="g6c2-s7sy wm-deco"/><path class="cf3uzcrzx wm-deco"/><path class="gsn30ubhe wm-k"/><path class="uc0yabbtt wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:scroll-text-blueprint" /></template>
