<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntgybcog.css';
import '../../css/m/mq9irnbcc.css';
import '../../css/h/hgpkc4b0w.css';
import '../../css/k/kniikcc3w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="mq9irnbcc"/><path class="hgpkc4b0w"/><path class="kniikcc3w"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="covid:transmission-virus-handshake" /></template>
