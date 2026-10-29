<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/u/uhbvnmlqs.css';
import '../../css/c/crjbpijjy.css';
import '../../css/e/e_6oe7ajk.css';
import '../../css/r/rvo70qbei.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="uhbvnmlqs"/><path class="crjbpijjy wm-a"/><path class="e_6oe7ajk wm-k"/><path class="rvo70qbei wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:plane-takeoff-sketch" /></template>
