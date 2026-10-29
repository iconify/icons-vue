<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/g/g2fqzc34l.css';
import '../../css/x/x6wurfbzt.css';
import '../../css/i/iwe_rn_rm.css';
import '../../css/r/ra358_b3i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="g2fqzc34l"/><path class="wm-a x6wurfbzt"/><path class="iwe_rn_rm wm-k"/><path class="ra358_b3i wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:volume-1-sketch" /></template>
