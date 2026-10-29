<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dt0cm9dhy.css';
import '../../css/d/d1dcdbblm.css';
import '../../css/f/f44jgxt3x.css';
import '../../css/t/thjectbkq.css';
import '../../css/i/ipkd9vbgw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="d1dcdbblm"/><path class="f44jgxt3x wm-a"/><path class="thjectbkq wm-a"/><path class="ipkd9vbgw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:thermometer-sun-duo" /></template>
