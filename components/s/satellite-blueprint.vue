<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s9nmekbvz.css';
import '../../css/s/s6hu1cmbz.css';
import '../../css/k/kydla-v8g.css';
import '../../css/c/caz3ylb4t.css';
import '../../css/e/e3ugiqbea.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s9nmekbvz"><path class="s6hu1cmbz wm-deco"/><path class="kydla-v8g wm-k"/><path class="caz3ylb4t wm-a"/><path class="e3ugiqbea wm-s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:satellite-blueprint" /></template>
