<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/v/vmm_qnbyp.css';
import '../../css/v/v6p4k08td.css';
import '../../css/g/gp-9ncbea.css';
import '../../css/m/mo5netbri.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="vmm_qnbyp"/><path class="v6p4k08td"/><path clip-rule="evenodd" class="gp-9ncbea"/><path class="mo5netbri"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons-print:umbrella-off" /></template>
