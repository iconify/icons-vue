<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/u/uyhjy_qbv.css';
import '../../css/l/lkpx07bzf.css';
import '../../css/u/uq-a8tbkj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="uyhjy_qbv"/><path class="lkpx07bzf wm-k"/><path class="uq-a8tbkj wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:vault-sketch" /></template>
