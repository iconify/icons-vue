<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s9nmekbvz.css';
import '../../css/j/jhdu2jbve.css';
import '../../css/i/im154wbuh.css';
import '../../css/w/wgdw9fsnj.css';
import '../../css/o/o25cc4zjh.css';
import '../../css/g/gd4v5cbxf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s9nmekbvz"><path class="jhdu2jbve wm-deco"/><path class="im154wbuh wm-deco"/><path class="wgdw9fsnj wm-deco"/><path class="o25cc4zjh wm-k"/><path class="gd4v5cbxf wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:stocking-blueprint" /></template>
