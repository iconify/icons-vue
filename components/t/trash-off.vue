<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/q/qh7mljbyv.css';
import '../../css/e/ed3mcy8qt.css';
import '../../css/x/x3ybkcknw.css';
import '../../css/m/mo5netbri.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<g class="cuyn6tgcc"><path class="qh7mljbyv"/><path class="ed3mcy8qt"/><path clip-rule="evenodd" class="x3ybkcknw"/><path class="mo5netbri"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons-pencil:trash-off" /></template>
