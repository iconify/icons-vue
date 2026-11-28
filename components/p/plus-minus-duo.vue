<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dt0cm9dhy.css';
import '../../css/f/fqmmacbbk.css';
import '../../css/o/oy7knh9mh.css';
import '../../css/f/fitl5vbyu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="fqmmacbbk"/><path class="oy7knh9mh"/><path class="fitl5vbyu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:plus-minus-duo" /></template>
