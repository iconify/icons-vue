<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l974u_srj.css';
import '../../css/h/hh0j4fnrz.css';
import '../../css/e/eddw_qbni.css';
import '../../css/n/n_f6npbzw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="l974u_srj"/><path class="hh0j4fnrz"/><path class="eddw_qbni"/><path class="n_f6npbzw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:zigbee2mqtt" /></template>
