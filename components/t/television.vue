<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/o/ooi-1y4um.css';
import '../../css/b/bk49d_bmy.css';
import '../../css/g/gm54u39ws.css';
import '../../css/l/ljz6bzfuv.css';
import '../../css/v/vbehv01rc.css';
import '../../css/n/n8nczbbdk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path class="ooi-1y4um"/><path class="bk49d_bmy"/><circle class="gm54u39ws"/><circle class="ljz6bzfuv"/><path class="vbehv01rc"/><path class="n8nczbbdk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-flat:television" /></template>
