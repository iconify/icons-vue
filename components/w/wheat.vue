<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/w/wx71ttb2k.css';
import '../../css/c/cci0p2vdm.css';
import '../../css/a/a912tebmm.css';
import '../../css/h/hg2_3g_gr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="wm-k wx71ttb2k"/><path class="cci0p2vdm wm-k"/><path class="a912tebmm wm-shadow"/><path class="hg2_3g_gr wm-shine"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-valentine:wheat" /></template>
