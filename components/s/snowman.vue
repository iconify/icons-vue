<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dt0cm9dhy.css';
import '../../css/d/d0dcmrbxa.css';
import '../../css/h/h2v4rg05k.css';
import '../../css/i/i6138id3q.css';
import '../../css/y/yrjl_cbrj.css';
import '../../css/x/xhfwlqbxc.css';
import '../../css/a/am9h9cbcf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="d0dcmrbxa"/><path class="h2v4rg05k wm-a"/><path class="i6138id3q wm-a"/><path class="wm-a yrjl_cbrj"/><path class="wm-s xhfwlqbxc"/><path class="am9h9cbcf wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:snowman" /></template>
