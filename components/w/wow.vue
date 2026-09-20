<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/a/abe4_nbce.css';
import '../../css/m/md_wqtycd.css';
import '../../css/y/yfs0kqb-c.css';
import '../../css/w/w6-q7vl-y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><circle class="abe4_nbce"/><circle class="md_wqtycd"/><circle class="yfs0kqb-c"/><path class="w6-q7vl-y"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:wow" /></template>
