<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/i/imqechvyp.css';
import '../../css/f/f-m6wkhvt.css';
import '../../css/i/i3f2j6b_u.css';
import '../../css/e/evvy2i13i.css';
import '../../css/p/povs420wf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="ft5dv1b6b"><path class="imqechvyp"/><path class="f-m6wkhvt"/><circle class="i3f2j6b_u"/><circle class="evvy2i13i"/><circle class="povs420wf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park:tickets-two" /></template>
