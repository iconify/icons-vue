<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/x/xzb_z2bum.css';
import '../../css/m/m5f5s512t.css';
import '../../css/g/guzqnlbhl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="xzb_z2bum"/><path class="m5f5s512t"/><path class="guzqnlbhl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand-color:microprocessor-computer-chip-search" /></template>
