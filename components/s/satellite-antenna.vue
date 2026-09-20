<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ituv_m4-l.css';
import '../../css/c/cth_9lbgc.css';
import '../../css/s/smj2mw7cm.css';
import '../../css/v/vl_m2cbkf.css';
import '../../css/t/tn51lubsq.css';
import '../../css/z/zhxc1wb9z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="ituv_m4-l"/><path class="cth_9lbgc"/><path class="smj2mw7cm"/><path class="vl_m2cbkf"/><path class="tn51lubsq"/><path class="zhxc1wb9z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:satellite-antenna" /></template>
