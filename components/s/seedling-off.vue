<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/d/d2kvgvbvc.css';
import '../../css/q/qc-apv10r.css';
import '../../css/n/n4byf3-kh.css';
import '../../css/s/spbi7bcof.css';
import '../../css/t/tdapwmbfy.css';
import '../../css/m/mo5netbri.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<g class="cuyn6tgcc"><g clip-rule="evenodd" class="d2kvgvbvc"><path class="qc-apv10r"/><path class="n4byf3-kh"/><path class="spbi7bcof"/><path class="tdapwmbfy"/></g><path class="mo5netbri"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons-pencil:seedling-off" /></template>
