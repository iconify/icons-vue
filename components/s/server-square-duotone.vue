<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/m/m2olt1beo.css';
import '../../css/d/dab4yko7u.css';
import '../../css/f/fkqe7rzrq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="m2olt1beo"/><path clip-rule="evenodd" class="dab4yko7u"/><path class="fkqe7rzrq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:server-square-duotone" /></template>
