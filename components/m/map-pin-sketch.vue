<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/b/b0pqdwr_b.css';
import '../../css/b/b5-ak3bmg.css';
import '../../css/h/hkvageoyh.css';
import '../../css/l/l5qqg4j2j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="b0pqdwr_b"/><path class="b5-ak3bmg wm-k"/><path class="hkvageoyh wm-k"/><path class="l5qqg4j2j wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:map-pin-sketch" /></template>
