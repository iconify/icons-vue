<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dt0cm9dhy.css';
import '../../css/t/tyb-2x2mm.css';
import '../../css/i/igrsv110m.css';
import '../../css/s/se-9fwbwp.css';
import '../../css/p/p-cqkx0gi.css';
import '../../css/m/m5s_ol08c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="tyb-2x2mm"/><path class="igrsv110m"/><path class="se-9fwbwp wm-a"/><path class="p-cqkx0gi"/><path class="m5s_ol08c wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:tombstone-duo" /></template>
