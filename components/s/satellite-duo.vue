<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dt0cm9dhy.css';
import '../../css/s/scdwi_bys.css';
import '../../css/r/ra5--iqdi.css';
import '../../css/p/pa-aaynvi.css';
import '../../css/k/kydla-v8g.css';
import '../../css/t/twlqflbgi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="scdwi_bys"/><path class="ra5--iqdi wm-a"/><path class="pa-aaynvi wm-s"/><path class="kydla-v8g"/><path class="twlqflbgi wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:satellite-duo" /></template>
