<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s9nmekbvz.css';
import '../../css/r/rj9jvq5qh.css';
import '../../css/b/bxjv56brc.css';
import '../../css/t/trt38b28x.css';
import '../../css/n/nctgfsyvy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s9nmekbvz"><path class="rj9jvq5qh wm-deco"/><path class="bxjv56brc wm-deco"/><path class="trt38b28x"/><path class="nctgfsyvy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:minimize-blueprint" /></template>
