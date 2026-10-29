<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dt0cm9dhy.css';
import '../../css/t/thi2wbcsz.css';
import '../../css/q/qw3cslx4k.css';
import '../../css/s/spev02xtm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="thi2wbcsz"/><path class="qw3cslx4k wm-a"/><path class="spev02xtm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:motorcycle-duo" /></template>
