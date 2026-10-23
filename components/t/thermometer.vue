<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xn5eo9bqs.css';
import '../../css/c/cqc2dpy0a.css';
import '../../css/m/m6dl7nbkg.css';
import '../../css/w/w03_94bgs.css';
import '../../css/y/y8raz3bfp.css';
import '../../css/q/qcgf0h-kr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="xn5eo9bqs"><path class="cqc2dpy0a"/><path class="m6dl7nbkg"/><path class="w03_94bgs"/><path class="y8raz3bfp"/><path class="qcgf0h-kr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="matita:thermometer" /></template>
