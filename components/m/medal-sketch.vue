<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/z/z_ml12bgo.css';
import '../../css/m/m23x9cwpi.css';
import '../../css/e/exiu9eq2v.css';
import '../../css/o/ovhif5-5j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="z_ml12bgo"/><path class="m23x9cwpi wm-a"/><path class="exiu9eq2v wm-k"/><path class="ovhif5-5j wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:medal-sketch" /></template>
