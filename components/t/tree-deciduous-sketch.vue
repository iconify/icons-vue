<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/m/m_cnwlbxs.css';
import '../../css/p/pk7vs7bdt.css';
import '../../css/c/cp8-p4b5u.css';
import '../../css/c/cbr2lvb4c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="m_cnwlbxs"/><path class="pk7vs7bdt wm-a"/><path class="cp8-p4b5u wm-k"/><path class="cbr2lvb4c wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:tree-deciduous-sketch" /></template>
