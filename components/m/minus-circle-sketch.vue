<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/o/otbqr_zzw.css';
import '../../css/z/z-cabbcfr.css';
import '../../css/q/qcxu_iduf.css';
import '../../css/t/tt67h0p8u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="otbqr_zzw wm-k"/><path class="wm-k z-cabbcfr"/><path class="qcxu_iduf wm-k"/><path class="tt67h0p8u wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:minus-circle-sketch" /></template>
