<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dt0cm9dhy.css';
import '../../css/d/ddt-lcbtr.css';
import '../../css/l/l51s4j92b.css';
import '../../css/x/xbx3o24fa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="ddt-lcbtr"/><path class="l51s4j92b wm-a"/><path class="xbx3o24fa"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:pilcrow-duo" /></template>
