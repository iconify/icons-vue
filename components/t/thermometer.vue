<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/ddvgu8bvv.css';
import '../../css/m/myu9avgru.css';
import '../../css/u/umtr24biu.css';
import '../../css/s/sq84s46_s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ddvgu8bvv"><path class="myu9avgru"/><path class="umtr24biu"/><path class="sq84s46_s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:thermometer" /></template>
