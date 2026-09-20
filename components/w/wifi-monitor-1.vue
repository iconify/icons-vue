<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/g/gczf6hboe.css';
import '../../css/m/m-s7vzbkn.css';
import '../../css/f/f-du83bit.css';
import '../../css/f/fmf_2ccuj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="gczf6hboe"/><path class="m-s7vzbkn"/><path class="f-du83bit"/><path class="fmf_2ccuj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand-color:wifi-monitor-1" /></template>
