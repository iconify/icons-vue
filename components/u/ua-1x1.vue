<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nv9qcacyl.css';
import '../../css/s/s7mvklbao.css';
import '../../css/w/wwoqqlb0b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<g class="nv9qcacyl"><path class="s7mvklbao"/><path class="wwoqqlb0b"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flag:ua-1x1" /></template>
