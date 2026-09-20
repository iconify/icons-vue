<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/q/q-evdcban.css';
import '../../css/v/vxpz4pvui.css';
import '../../css/c/cdsox1w9v.css';
import '../../css/x/x9mvs1_as.css';
import '../../css/v/vqyephr6g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="q-evdcban"/><path class="vxpz4pvui"/><path clip-rule="evenodd" class="cdsox1w9v"/><path class="x9mvs1_as"/><path clip-rule="evenodd" class="vqyephr6g"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons-pencil:monitor" /></template>
