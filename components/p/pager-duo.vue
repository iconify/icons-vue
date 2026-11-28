<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/icgk-wbnx.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/s/sb-u7hbtr.css';
import '../../css/n/n7nnzhblg.css';
import '../../css/e/e5edqev6a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="icgk-wbnx secondary"/><g class="dt0cm9dhy primary"><path class="sb-u7hbtr"/><path class="n7nnzhblg"/><path class="e5edqev6a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:pager-duo" /></template>
