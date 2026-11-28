<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i0r16e4cs.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/w/wp1q2ntpc.css';
import '../../css/y/yylyrccfn.css';
import '../../css/q/qjzyurbpi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i0r16e4cs secondary"/><g class="dt0cm9dhy primary"><path class="wp1q2ntpc"/><path class="yylyrccfn"/><path class="qjzyurbpi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:map-pin-off-duo" /></template>
