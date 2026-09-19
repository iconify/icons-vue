<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntgybcog.css';
import '../../css/m/m-7u57b3n.css';
import '../../css/d/d3i_dbbrj.css';
import '../../css/e/ep70jebpf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="m-7u57b3n"/><path class="d3i_dbbrj"/><path class="ep70jebpf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:sms-code" /></template>
