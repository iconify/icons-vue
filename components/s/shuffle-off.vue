<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/w/wplr_9b2m.css';
import '../../css/m/m5cuh9a3g.css';
import '../../css/k/kz72l8bmh.css';
import '../../css/m/mo5netbri.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="wplr_9b2m"/><path clip-rule="evenodd" class="m5cuh9a3g"/><path clip-rule="evenodd" class="kz72l8bmh"/><path class="mo5netbri"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons-pencil:shuffle-off" /></template>
