<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/x/x36h_kb1w.css';
import '../../css/l/l1gz4_bhl.css';
import '../../css/d/dzkxljb6w.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGB2bN7mun"><g class="ft5dv1b6b"><path class="x36h_kb1w"/><path class="l1gz4_bhl"/><path class="dzkxljb6w"/></g></mask></defs><path mask="url(#SVGB2bN7mun)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:voice-message" /></template>
