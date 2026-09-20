<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/e/exdmtsbst.css';
import '../../css/c/cq0pnj2xi.css';
import '../../css/u/utvuz8bri.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="exdmtsbst"/><path class="cq0pnj2xi"/><path class="utvuz8bri"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand-color:meeting-user-man-stress" /></template>
