<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/i/iv4z4zbpc.css';
import '../../css/j/jjq_smbpx.css';
import '../../css/q/qk1oudndu.css';
import '../../css/n/nbkmm9bhe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="iv4z4zbpc"/><path clip-rule="evenodd" class="jjq_smbpx"/><path class="qk1oudndu"/><path class="nbkmm9bhe"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons-print:syringe-off" /></template>
