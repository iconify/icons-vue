<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/o/oc-a5jbga.css';
import '../../css/y/yy6sjibep.css';
import '../../css/x/xjqifybeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="oc-a5jbga"/><path class="yy6sjibep"/><path class="xjqifybeo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:zap-sketch" /></template>
