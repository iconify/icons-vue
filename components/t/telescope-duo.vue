<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dt0cm9dhy.css';
import '../../css/p/pqwfdvh6t.css';
import '../../css/b/b0pdi0-3d.css';
import '../../css/n/nboiatbai.css';
import '../../css/k/kbj8nvb7i.css';
import '../../css/p/ptk50absq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="pqwfdvh6t"/><path class="b0pdi0-3d"/><path class="nboiatbai wm-a"/><path class="kbj8nvb7i"/><path class="ptk50absq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:telescope-duo" /></template>
