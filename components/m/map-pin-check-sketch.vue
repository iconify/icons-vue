<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/m/m7_vfacpm.css';
import '../../css/u/uhvpqyzxp.css';
import '../../css/s/s-zhlbbmg.css';
import '../../css/a/at8xfhyjc.css';
import '../../css/x/x_y_7lbhg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="m7_vfacpm"/><path class="uhvpqyzxp wm-k"/><path class="s-zhlbbmg wm-a"/><path class="at8xfhyjc wm-k"/><path class="wm-a x_y_7lbhg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:map-pin-check-sketch" /></template>
