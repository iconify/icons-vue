<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntgybcog.css';
import '../../css/y/yjy_lob3u.css';
import '../../css/o/ooks3obcj.css';
import '../../css/s/sk8kac_qm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="yjy_lob3u"/><path class="ooks3obcj"/><path class="sk8kac_qm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:napkins-01" /></template>
