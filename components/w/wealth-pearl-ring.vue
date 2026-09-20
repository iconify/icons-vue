<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/i/iuumq_xza.css';
import '../../css/v/vbjcoebvr.css';
import '../../css/q/q3q5_acsu.css';
import '../../css/q/q00c_qbka.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="iuumq_xza"/><path class="vbjcoebvr"/><path class="q3q5_acsu"/><path class="q00c_qbka"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand-color:wealth-pearl-ring" /></template>
