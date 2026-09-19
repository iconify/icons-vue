<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y5cg8fb9r.css';
import '../../css/h/hs15a5npu.css';
import '../../css/q/qnuwo-b8n.css';
import '../../css/f/fi_rz_b5r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="y5cg8fb9r"><path class="hs15a5npu"/><path class="qnuwo-b8n"/><path class="fi_rz_b5r"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:sailboat" /></template>
