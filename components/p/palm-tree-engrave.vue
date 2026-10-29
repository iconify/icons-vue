<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/m/mrvy4_b6j.css';
import '../../css/y/ymz7xhbvh.css';
import '../../css/w/wby-z7brq.css';
import '../../css/u/ukjbh_bly.css';
import '../../css/n/nrb_pjbun.css';
import '../../css/q/qcfnobbty.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="mrvy4_b6j wm-k"/><path class="wm-a ymz7xhbvh"/><path class="wby-z7brq wm-shadow"/><path class="ukjbh_bly wm-k"/><path class="nrb_pjbun wm-k"/><path class="qcfnobbty wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:palm-tree-engrave" /></template>
