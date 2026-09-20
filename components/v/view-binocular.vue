<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/b/b2nzvx1us.css';
import '../../css/s/s_plwmgtd.css';
import '../../css/q/qzzhnccem.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="b2nzvx1us"/><path class="s_plwmgtd"/><path class="qzzhnccem"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand-color:view-binocular" /></template>
