<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dt0cm9dhy.css';
import '../../css/l/l3y24d3cp.css';
import '../../css/l/ltkl8-bml.css';
import '../../css/d/ddyqfljgi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="l3y24d3cp"/><path class="ltkl8-bml"/><path class="ddyqfljgi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:wallet" /></template>
