<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/v/vdvfy6qjl.css';
import '../../css/l/l-1418vhh.css';
import '../../css/a/a1pvkxohd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="vdvfy6qjl"/><path class="l-1418vhh"/><path class="a1pvkxohd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:wrench-sketch" /></template>
