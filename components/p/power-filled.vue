<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/r/r7g2pcbpg.css';
import '../../css/g/gx1dibbnm.css';
import '../../css/u/ucj31ibdn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="r7g2pcbpg"/><path class="gx1dibbnm"/><path class="ucj31ibdn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:power-filled" /></template>
