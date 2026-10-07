<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntgybcog.css';
import '../../css/n/nkpbhqfkh.css';
import '../../css/b/b64l0dbmf.css';
import '../../css/t/t881ox47o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="nkpbhqfkh"/><path class="b64l0dbmf"/><path class="t881ox47o"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:rotate-camera-right" /></template>
