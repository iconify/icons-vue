<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/t/t2fkmoivg.css';
import '../../css/j/j1bbo3bbt.css';
import '../../css/j/j43jx7okr.css';
import '../../css/u/uulvq9b8e.css';
import '../../css/r/rurpwmbun.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="t2fkmoivg"/><path class="j1bbo3bbt wm-k"/><path class="j43jx7okr wm-a"/><path class="uulvq9b8e wm-k"/><path class="rurpwmbun wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:snow-globe-sketch" /></template>
