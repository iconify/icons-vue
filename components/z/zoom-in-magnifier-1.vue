<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/i/i43u13dxb.css';
import '../../css/k/kmc5z7fpw.css';
import '../../css/n/njudr8bor.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="i43u13dxb"/><path class="kmc5z7fpw"/><path class="njudr8bor"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand-color:zoom-in-magnifier-1" /></template>
