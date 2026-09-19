<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/n/nctb2ac4r.css';
import '../../css/h/hn-as6b7m.css';
import '../../css/s/szn9-zbto.css';
import '../../css/t/ttjsdwbbs.css';
import '../../css/x/xg7tgyb7v.css';
import '../../css/g/gq_x69oxs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<g class="cuyn6tgcc"><g class="nctb2ac4r"><rect class="hn-as6b7m"/><path clip-rule="evenodd" class="szn9-zbto"/></g><path class="ttjsdwbbs"/><path class="xg7tgyb7v"/><path clip-rule="evenodd" class="gq_x69oxs"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons:trash-print" /></template>
