<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/v/v3c0odnjd.css';
import '../../css/g/gwpevo8qp.css';
import '../../css/o/o0m_us_lw.css';
import '../../css/r/rqi-mcbpo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="v3c0odnjd"/><path class="gwpevo8qp wm-k"/><path class="o0m_us_lw wm-k"/><path class="rqi-mcbpo wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:megaphone-sketch" /></template>
