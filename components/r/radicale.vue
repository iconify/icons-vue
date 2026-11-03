<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qsnyatslk.css';
import '../../css/e/eacht384o.css';
import '../../css/e/eomgn6xaw.css';
import '../../css/v/vabgvhplk.css';
import '../../css/t/tawi2lsdc.css';
import '../../css/v/vr2clrb9d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":200,"height":300};
const content = `<path class="qsnyatslk"/><path class="eacht384o"/><g class="eomgn6xaw"><path class="vabgvhplk"/><path class="tawi2lsdc"/><path class="vr2clrb9d"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:radicale" /></template>
