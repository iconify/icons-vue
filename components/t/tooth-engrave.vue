<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/w/wo03t_npi.css';
import '../../css/o/ozwb22glz.css';
import '../../css/w/wjf1ikbgx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="wo03t_npi"/><path class="ozwb22glz wm-shadow"/><path class="wjf1ikbgx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:tooth-engrave" /></template>
