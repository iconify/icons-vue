<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntgybcog.css';
import '../../css/j/j7lgzkbaq.css';
import '../../css/x/xnxh71obt.css';
import '../../css/h/hvgzjjb7d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="j7lgzkbaq"/><path class="xnxh71obt"/><path class="hvgzjjb7d"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:sms-search" /></template>
