<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/c/cvoru2btt.css';
import '../../css/r/r9pevev-u.css';
import '../../css/u/u606cnbwx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="cvoru2btt wm-a"/><path class="r9pevev-u wm-k"/><path class="u606cnbwx wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:monitor-sketch" /></template>
