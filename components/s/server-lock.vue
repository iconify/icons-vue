<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/o/oysn7k5ti.css';
import '../../css/x/xbs_vnzhd.css';
import '../../css/u/utnt0dbeq.css';
import '../../css/h/hk-r7ubdz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="oysn7k5ti"/><path class="xbs_vnzhd"/><path class="utnt0dbeq"/><path class="hk-r7ubdz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand-color:server-lock" /></template>
