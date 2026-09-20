<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/m/m01ctjbzw.css';
import '../../css/s/s0r2zwbma.css';
import '../../css/f/fu46eccto.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="m01ctjbzw"/><path class="s0r2zwbma"/><path class="fu46eccto"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand-color:network-monitor-transfer-arrow-1" /></template>
