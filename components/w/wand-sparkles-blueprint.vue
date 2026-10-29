<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s9nmekbvz.css';
import '../../css/q/qen4ux05d.css';
import '../../css/a/afx3wjhic.css';
import '../../css/c/c-frn5b_h.css';
import '../../css/n/ni2s7jrqo.css';
import '../../css/k/kveoqhyms.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s9nmekbvz"><path class="qen4ux05d wm-deco"/><path class="afx3wjhic wm-deco"/><path class="c-frn5b_h wm-deco"/><path class="ni2s7jrqo wm-k"/><path class="kveoqhyms wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:wand-sparkles-blueprint" /></template>
