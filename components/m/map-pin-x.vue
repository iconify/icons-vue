<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nrj6p8qat.css';
import '../../css/a/ah1hcpbhw.css';
import '../../css/z/zv6cqnbnp.css';
import '../../css/q/qrid-hb2b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="ah1hcpbhw"/><circle class="zv6cqnbnp"/><path class="qrid-hb2b"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:map-pin-x" /></template>
