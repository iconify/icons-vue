<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s9nmekbvz.css';
import '../../css/i/iybtqzc1y.css';
import '../../css/r/rbzq4bjzv.css';
import '../../css/q/qcj08-q2z.css';
import '../../css/w/w302-hd8l.css';
import '../../css/k/kucshig4r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s9nmekbvz"><path class="iybtqzc1y wm-deco"/><path class="rbzq4bjzv wm-deco"/><path class="qcj08-q2z wm-k"/><path class="w302-hd8l wm-a"/><path class="kucshig4r wm-k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:receipt-text-blueprint" /></template>
