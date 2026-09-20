<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/d/dpf22ybrv.css';
import '../../css/m/mjbq1q3lt.css';
import '../../css/n/nxp5z5bgo.css';
import '../../css/y/y5i2yrbgs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="dpf22ybrv"/><path class="mjbq1q3lt"/><path class="nxp5z5bgo"/><path class="y5i2yrbgs"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand-color:office-paper-binder" /></template>
