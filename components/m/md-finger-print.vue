<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yh20y2bau.css';
import '../../css/v/vf1c710_a.css';
import '../../css/l/lhow-8b0x.css';
import '../../css/m/mge_w5m3i.css';
import '../../css/k/klnn7_i_v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="yh20y2bau"/><path class="vf1c710_a"/><path class="lhow-8b0x"/><path class="mge_w5m3i"/><path class="klnn7_i_v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:md-finger-print" /></template>
