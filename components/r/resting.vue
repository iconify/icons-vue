<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nz_20wbpz.css';
import '../../css/r/r53mumbjb.css';
import '../../css/h/hmg-5dugg.css';
import '../../css/q/qp833-mnc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="nz_20wbpz"><path class="r53mumbjb"/><path class="hmg-5dugg"/><path class="qp833-mnc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:resting" /></template>
