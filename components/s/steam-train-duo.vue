<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/phm30sbfb.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/x/xhu828bgh.css';
import '../../css/m/mz1560bnj.css';
import '../../css/i/ixbwkv4mz.css';
import '../../css/w/wk9de4znk.css';
import '../../css/u/ur3_tunjd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="phm30sbfb secondary"/><g class="dt0cm9dhy primary"><path class="xhu828bgh"/><path class="mz1560bnj"/><path class="ixbwkv4mz"/><path class="wk9de4znk"/><path class="ur3_tunjd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:steam-train-duo" /></template>
