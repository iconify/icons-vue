<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/x/x7a_enb4j.css';
import '../../css/g/gvf974yhc.css';
import '../../css/r/ru5z24bqz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="x7a_enb4j"/><path clip-rule="evenodd" class="gvf974yhc"/><path class="ru5z24bqz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:monitor-stop-duotone" /></template>
