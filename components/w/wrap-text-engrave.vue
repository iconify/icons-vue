<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/l/lmiso_bzd.css';
import '../../css/x/xolfzwbae.css';
import '../../css/a/a9objzbor.css';
import '../../css/q/qnns3cbcc.css';
import '../../css/n/nq91dpkwm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="lmiso_bzd wm-k"/><path class="wm-a xolfzwbae"/><path class="a9objzbor wm-shadow"/><path class="qnns3cbcc wm-k"/><path class="nq91dpkwm wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:wrap-text-engrave" /></template>
